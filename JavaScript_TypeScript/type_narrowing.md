type narrowing means checking a value before we operate on it so TypeScript can work out a more specific type inside the code. It's how you turn "string or number" into "definitely a string" and then use string methods on it.

we cn use it to git rid of the nulls and the undeficed before we operate on them