---
title: .calls(filter, options)
sidebar:
  label: .calls()
  order: 3
---
Returns an array of all calls to fetch matching the given `filter` and `options`. Each call is returned as a `[url, options]` array. If `fetch` was called using a `Request` instance, the `url` and `options` will be inferred from it, and the original `Request` will be available as a `request` property on this array.
