---
title: Arrays equal Strings?!
permalink: wtf/arrays-equal-strings
source:
  url: https://twitter.com/kd2luw/status/992096570802765824
  class: twitter
description: So... Arrays equal strings, but not themselves?!
---

```
var a = [1,2,3];
var b = [1,2,3];
var c = '1,2,3';

a == c; // true
b == c; // true
a == b; // false
```

*shuts laptop forever*