# Personal profile of software engineering skills

⬜ Optional, 🟦 Required for all, 🟨 Required for js, 🟩 Learned, 🟥 Declined

## Fundamental concepts

| Syntax               | Statements            | Functions             | Data structures     | Process & style      |
|----------------------|-----------------------|-----------------------|---------------------|----------------------|
| 🟦 value             | 🟦 if                 | 🟦 recursion          | 🟦 array            | 🟦 refactoring       |
| 🟦 identifier        | 🟦 loops              | 🟦 function           | 🟦 instance         | 🟦 code review       |
| 🟦 variable          | 🟦 assignment         | 🟦 return             | 🟦 object           | 🟦 antipatterns      |
| 🟦 constant          | 🟨 prototype          | 🟦 signature          | 🟦 collection       | 🟦 paradigm          |
| 🟦 scalar            | 🟦 class              | 🟦 argument           | 🟦 hash table       | 🟦 algorithm         |
| 🟦 literal           | 🟦 while              | 🟦 parameter          | 🟦 linked list      | 🟦 magic numbers     |
| 🟦 expression        | 🟦 do..while          | 🟦 pure               | 🟦 queue            | 🟦 hardcode          |
| 🟦 heap              | 🟦 for                | 🟦 function           | 🟦 stack            | 🟦 complexity        |
| 🟦 type              | 🟨 for..in            | 🟦 side effects       | 🟦 deque            | 🟦 decomposition     |
| 🟦 primitive types   | 🟨 for..of            | 🟦 closure            | 🟦 serialization    | ⬜️ spaghetti         |
| 🟦 reference         | 🟨 for await          | 🟦 partial            | 🟦 mixin, extend    | ⬜️ silver bullet     |
| 🟦 flag              | 🟦 throw              | ⬜️ curry              | 🟨 iterator         | ⬜️ not invented here |
| 🟦 lexical scope     | 🟦 try..catch         | 🟦 chaining           | 🟨 typed arrays     | 🟦 dead code         |
| 🟦 code block        | 🟦 equality operators | 🟦 higher order       | 🟨 Map              | 🟦 unreachable code  |
| 🟨 Object            | 🟦 logical operators  | 🟦 callback           | 🟨 Set              | 🟦 duplicate code    |
| 🟨 this              | 🟦 bitwise operators  | 🟦 listener           | ⬜️ weak collections | 🟦 exception         |
| 🟨 arrow function    | 🟦 break, continue    | ⬜️ pipe               | ⬜️ Proxy            | 🟦 return early      |
| 🟨 generator         | 🟦 switch             | ⬜️ memoize            | ⬜️ Symbol           | 🟦 linter            |
| 🟨 async function    | 🟨 new Error          | 🟦 factory            | 🟨 string parsing   | ⬜️ prettier          |
| 🟨 call, bind, apply |                       | 🟦 pool               | 🟨 timers           | 🟦 unittest          |
| 🟨 Array             |                       | 🟦 wrapper            | 🟨 EventEmitter     | 🟦 git               |
| 🟨 instanceof        |                       | 🟨 default parameters | 🟨 RegExp           | 🟦 github            |
| 🟨 ...spread         |                       | 🟦 lambda             | 🟨 global           | 🟨 node.js           |
| 🟨 ...rest           |                       |                       | 🟨 undefined        | 🟨 npm               |
| 🟨 typeof            |                       |                       | 🟦 null             |                      |

## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques            |
|------------------------|--------------------------------|---------------------|-----------------------|
| 🟦 Callback-last       | 🟦 Timers                      | 🟦 Event Loop       | 🟦 async.js library   |
| 🟦 Error-first         | 🟦 setImmediate                | 🟦 Async error      | 🟦 Async composition  |
| 🟦 Promise             | 🟦 nextTick                    | 🟦 try..catch       | 🟦 Rx.js              |
| 🟦 Async function      | 🟦 AbortController             | 🟦 Non-blocking     | 🟦 Sequential async   |
| 🟦 await               | 🟦 Promise unhandled rejection | 🟦 Async I/O        | 🟦 Parallel async     |
| 🟦 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟦 Promise.all        |
| 🟦 Async Generator     | 🟦 child_process               | 🟦 CAS operations   | 🟦 Promise.allSettled |
| 🟦 Async Iterator      | 🟦 worker_threads              | 🟦 epoll            | 🟦 Promise.race       |
| 🟦 Thenable            | 🟦 Atomics                     | 🟦 kqueue           | 🟦 Promise.any        |
| 🟦 EventEmitter        | 🟦 Blockeing operations        | 🟦 Completion ports | 🟦 Web Locks API      |
| 🟦 Cancelable callback | 🟦 Non-blocking loop for Array | 🟦 Event ports      | 🟦 Async Pool         |
| 🟦 Cancelable Promise  | 🟦 High resolution clock       | 🟦 libuv            | 🟦 Thread Pool        |
| 🟦 Asynchronous Queue  | 🟦 Callback hell               | 🟦 Race conditions  | 🟦 callbackify        |
| 🟦 Future              | 🟦 Promise hell                | 🟦 Dead locks       | 🟦 promisify          |
| 🟦 Deferred            | 🟦                             | 🟦 Live locks       | 🟦 IPC                |
| 🟦 Observer            | 🟦                             | 🟦 Actor Model      | 🟦 Channel API        |
| 🟦 Async Collector     | 🟦                             | 🟦                  | 🟦                    |
| 🟦 Coroutine           | 🟦                             | 🟦                  | 🟦                    |
| 🟦 Goroutine           | 🟦                             | 🟦                  | 🟦                    |

TODO: Revealing Constructor
