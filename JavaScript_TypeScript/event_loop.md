JavaScript runs on a single thread so the event loop  decides what runs next 

Order of execution: synchronous code then all microtasks (promises, after-await code) then macrotask (timers, I/O, events) then repeat.

even if the microtask is fulfiled it still waits the sync code to run first 

another issue is long sync loop code freeze the page because all the micro and macro tasks don't run until the sync finish first 