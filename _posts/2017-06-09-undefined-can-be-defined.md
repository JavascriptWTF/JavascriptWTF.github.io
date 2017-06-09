---
title: Undefined can be defined
permalink: wtf/undefined-can-be-defined
source:
  url: https://www.smashingmagazine.com/2011/05/10-oddities-and-secrets-about-javascript/#10-undefined-can-be-defined
  class: external-link
---

```
> var t
< undefined

> t == undefined
< true      // Ok, that makes sense

> t = "Defined"
< "Defined" // Ok...
> var t
< undefined // ... so far, so good...
> t == undefined
< false     // ... What now?
```
