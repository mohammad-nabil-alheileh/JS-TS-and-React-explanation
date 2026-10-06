A shallow copy copies only the top level. Nested objects and arrays are still shared with the original.

A deep copy copys everything, so nothing is shared.

when we don't want to copy the refrences too deep copy is not the best approuch becuase it's  slow so the better way is shallow copy alongside the immutable update to be sure that any unchanged refrecnce doen't effect the re-rendering of react comapanet