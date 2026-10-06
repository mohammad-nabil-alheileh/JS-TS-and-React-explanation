Async/await it's a syntax built on top of Promises, more strucured, more readable and better in some cases like chain hell

it have 2 parts 

- async : tells the code that it an async code and it always return a promise

- await : waits for a Promise to settle and gives us its fulfilled value.

for it to work the best it could it have to be in try/catch because if the promise fails we have what to handle it 