### Hi there 👋

My name is Edy Silva. I'm a software engineer who loves to experiment with different tools to discover their full potential. I enjoy recreating existing tools just to understand how they work internally. To document my discoveries and thoughts, I write them in blog posts.

### Open source contributions

Open source is another way to explore different scenarios where I could make contributions in JavaScript, Ruby, Elixir, and Erlang. Since last year, I have focused my efforts on the [Node.Js](https://github.com/nodejs/node) project, where I am now a core collaborator. In Node.JS, I could work on a variety of issues where I can highlight two main cases:

#### [SQLite backup implementation](https://github.com/nodejs/node/pull/56253)

This patch introduced the [backup API](https://nodejs.org/api/sqlite.html#sqlitebackupsourcedb-path-options) to the `node:sqlite` module. It was pleasant to make it work since I could touch different areas in Node.JS codebase. That was my second C++ contribution. Besides that, I dealt with [libuv threadpool](https://docs.libuv.org/en/v1.x/threadpool.html) to ensure the backup process was efficient.

#### [Fix AbortSignal memory leak](https://github.com/nodejs/node/pulls?q=is%3Apr+is%3Aclosed+author%3Ageeksilva97+signals+)

In this fix, I could explore the profiling capabilities of Node.JS and Chrome. I used, for the first time, components like [WeakRef](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakRef) and [FinalizationRegistry](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/FinalizationRegistry).

Writing tests that called Garbage Collector were also a good challenge!

### Get in touch

- [https://blog.codeminer42.com/author/antonio-barbosa/](https://blog.codeminer42.com/author/antonio-barbosa/) - My posts at CodeMiner42's Blog
- [https://codesilva.github.io/](https://codesilva.github.io/) - Blog com ensaios em português 🇧🇷

Checkout more at [https://beacons.ai/edigleyssonsilva](https://beacons.ai/edigleyssonsilva)
