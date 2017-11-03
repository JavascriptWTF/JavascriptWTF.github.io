---
title: Appending a string to null treats it as a string
permalink: wtf/append-string-to-null
description: Yeah... nulling... that's what I meant...
---

```
t = 'test'
undefined

t += 'ing'
"testing"

t=null
null

t += 'ing'
"nulling"
```
