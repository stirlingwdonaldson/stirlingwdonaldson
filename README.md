# Stirling Donaldson

```asm
  .ORIG x3000

  LEA R0, NAME  ; load name into R0
  PUTS          ; print R0

  HALT
  NAME  .STRINGZ "Hi, I'm Stirling Donaldson!"
  .END
```


```text
→ stirlingwdonaldson git:(main)laser -a README.asm && laser.obj

  Hello, I'm Stirling Donaldson!

```
