in React doesn't get triggerd when object value change is re-renders when the refrence change because it compare refrences not values, so when we want to triger a re-render we choose the immutable way so we make a new refrence with the new values 

examples 

Objects

const next = { ...user, age: 21 };            // update a field

const { age, ...withoutAge } = user;          // remove a field

Arrays

const added   = [...items, newItem];                         // add

const removed = items.filter(i => i.id !== id);              // remove

const updated = items.map(i =>
  i.id === id ? { ...i, done: true } : i                     // update one
);