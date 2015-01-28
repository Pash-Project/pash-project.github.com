---
layout: page
title: F.A.Q
permalink: /faq/
---


# How to I get rid of the strange characters in my terminal after running pash?

```
$ mono Source/PashConsole/bin/Debug/Pash.exe
[%?%p1%{8}%<%t37%e%p1%{16}%<%t9%p1%{8}%-%d%...
```

Try starting Pash like this: `TERM=xterm mono Source/PashConsole/bin/Debug/Pash.exe`
