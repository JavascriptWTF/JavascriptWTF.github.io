---
title: Null Comparison
permalink: wtf/null-comparison
source:
  url: https://gist.github.com/MichalZalecki/c964192f830360ce6361#file-wtf-js-L31
  class: github
---

```
/* null comparation */

> 0 > null
false

> 0 >= null
true

> 0 == null
false

> 0 <= null
true

> 0 < null
false

> typeof null
'object'

> null instanceof Object
false
```
