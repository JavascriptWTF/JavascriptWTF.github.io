---
title: Assigning to and through literals and undefined
permalink: wtf/assign-through-literals-and-undefined
source:
  url: https://stackoverflow.com/a/71872185/3029882
  class: external-link
description: Not only assign to undefined, but assign a value through it.
redirect_from:
  - /wtf/assign-through-literals-and-undefined.md
---

```
> 'abc'[1] = 'B' // this does NOT modify the 'abc' string literal (so far so good) but returns 'B'
> let B = 'abc'[1] = 'B' // so this does actually assign 'B' to B"
> undefined = 'B' // this does not change undefined (so far so good) but also returns 'B'
> let B = undefined = 'B' // so this does actually assign 'B' to B", through undefined
```

So not only can you assign something to undefined, but it is possible to assign a value through it.
