## What is Node?
Node is JavaScript runtime environment that runs on the V8 engine (by default) and executes JavaScript code outside a web browser. Latest version: `18.7.0` (as of Aug, 2022)

## Difference between Node and JavaScript?
They are not comparable. JavaScript is a programming language but Node is a runtime environment (Just like a brower)

## What is V8 engine and what are all it's alternative?
V8 is a Javascript engine which runs the JavaScript code.
![v8 engine](img/v8_engine.png)
alternatives : SpiderMonkey (FireFox), Chakara (MicroSoft)
## CallBack vs Promises

## async await

## JavaScript vs EcmaScript?

## Reference
- [What the heck is event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- [The Node.js Event Loop: Not So Single Threaded](https://youtu.be/zphcsoSJMvM)
    - It's true that all JavaScript executed by Node.js is run in a single thread, but JS isn't all. The event loop (libuv), written in C++, is multi-threaded! Come learn how the event loop works, how it affects performance, and how you can use it your advantage!
    - Walks over multiple benchmark examples on how event loop works
    - Event loop is not part of v8 engine 🤔