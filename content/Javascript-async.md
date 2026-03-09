---
tags:
  - javascript
  - async
---
# Asynchronous JavaScript

JavaScript is single-threaded but handles concurrency through an event loop and non-blocking I/O.

## Callbacks

The original pattern for async operations. Can lead to deeply nested "callback hell."

## Promises

A cleaner way to handle async results with `.then()` and `.catch()` chaining.

```javascript
fetch("/api/data")
  .then(res => res.json())
  .then(data => console.log(data));
```

## Async/Await

Syntactic sugar over Promises that makes async code read like synchronous code.

```javascript
async function loadData() {
  const res = await fetch("/api/data");
  const data = await res.json();
  return data;
}
```

## Parent

- [[Javascript]]
