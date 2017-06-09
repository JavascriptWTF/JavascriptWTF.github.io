---
title: WTF Strings?
permalink: wtf/wtf-strings
source:
  url: https://gist.github.com/MichalZalecki/c964192f830360ce6361#file-wtf-js-L151
  class: github
description: Strings are not strings but they are equal
---

```
> 'wtf' instanceof String
false

> typeof 'wtf'
'string'

> typeof String('wtf')
'string'

> String('wtf') === 'wtf'
true
```
