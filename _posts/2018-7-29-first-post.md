---
layout: posts
title: YDKJS Scope & Closures Notes
description: Notes on YDKJS Scope & Closures
image: null
category: javascript
---

# YDKJS: Scope & Closures

---

1. `Lexing`
2. ``
3. `Code-Generation`

`Scope`
`Engine`

`State`: the ability to store a value into a variable and take that value out.

## Lookups

`LHS`: Left-hand lookup
`RHS`: Right-hand lookup

Example:

```javascript
function myExample(a) {
    var b = 2;
    console.log(a + b);
}
myExample(5);  // 7
```
