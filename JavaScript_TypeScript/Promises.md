The promises we use with the code that needs time like fetching data from an API, It represents a value that will be available later, when it gets the response either reslove or rejecte. 

The promise have 3 states : 

- pending : still waiting a response 

- rejects : operation failed

- Fulfilled : operation succeeded

it have 4 parts
- promise : to manually tell the code know it works as a promise (async)

- .then : Runs when the promise is fulfilled it works in a chain each .then() can return a value or another Promise, The next .then() receives the value returned by the previous .then().

- .catch : handles a reject promise or an error inside the chain 

- .finally : works at the last eaither the promise failed or succeeds or not example of it is to hide the loading spinner

there are 4 methods (Promise.all)

- all : the promise succeeds only when all promises is fulfilled otherwise it reject the promise.all we use it when we need all the results

- allSettled : wait for all the promisesto finish even if it's reected we use it when we want to know the result of th eoperations 

- race : it settles with the first promise finish even if it's rejected 

- any : if at least one fulfills is does succeeds if all reject it rejects