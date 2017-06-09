---
title: Undefined can be defined
permalink: wtf/undefined-can-be-defined
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

Source: [www.smashingmagazine.com/2011/05/10-oddities-and-secrets-about-javascript](https://www.smashingmagazine.com/2011/05/10-oddities-and-secrets-about-javascript/#10-undefined-can-be-defined)
