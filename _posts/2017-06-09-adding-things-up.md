---
title: Adding things up
permalink: wtf/adding-things-up
source:
  url: https://charlieharvey.org.uk/page/javascript_the_weird_parts
  class: external-link
description: Of course array plus array is string!
---

```
> []+[] // ""
> []+{} // "[object Object]"
> {}+[] // 0
> {}+{} // NaN
```

Well those are some nice and consistent results!
