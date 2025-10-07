# Stirling Donaldson

```asm
  .ORIG x3000

  LEA R0, NAME  ; load name into R0
  PUTS          ; print R0

  HALT
  NAME  .STRINGZ "Hi, I am Stirling Donaldson!"
  .END
```


```text
→ stirlingwdonaldson git:(main) laser -a README.asm && README.obj

  Hi, I am Stirling Donaldson!

```
