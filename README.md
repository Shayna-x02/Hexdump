# Hexdump

This is a cross-platform hexdump utility composing of a single file. This is as lightweight and portable as it gets. The architecture (32/64) can be changed in the makefile before running it.

### File Example
```
hexdump -f SomeFile.exe
```
### Piping Example
``` 
ipconfig | hexdump
```

### Sample Output
This is the hexdump of a Ruby script. 
```
Offset(h)   |01|02|03|04|05|06|07|08|09|0A|0B|0C|0D|0E|0F|
            |**|**|**|**|**|**|**|**|**|**|**|**|**|**|**|
00000000    |72|65|71|75|69|72|65|20|22|66|69|6C|65|75|74|    require."fileut
00000010    |69|6C|73|22|0D|0A|0D|0A|6F|6C|64|5F|6D|6F|64|    ils"....old_mod
00000020    |73|20|3D|20|6F|70|65|6E|28|22|6F|6C|64|2E|74|    s.=.open("old.t
00000030    |78|74|22|2C|20|22|72|22|29|20|64|6F|20|7C|73|    xt",."r").do.|s
00000040    |74|72|65|61|6D|7C|20|73|74|72|65|61|6D|2E|72|    tream|.stream.r
00000050    |65|61|64|6C|69|6E|65|73|20|65|6E|64|0D|0A|6E|    eadlines.end..n
00000060    |65|77|5F|6D|6F|64|73|20|3D|20|6F|70|65|6E|28|    ew_mods.=.open(
00000070    |22|63|75|72|72|65|6E|74|2E|74|78|74|22|2C|20|    "current.txt",.
00000080    |22|72|22|29|20|64|6F|20|7C|73|74|72|65|61|6D|    "r").do.|stream
00000090    |7C|20|73|74|72|65|61|6D|2E|72|65|61|64|6C|69|    |.stream.readli
000000A0    |6E|65|73|20|65|6E|64|0D|0A|0D|0A|65|6E|61|62|    nes.end....enab
000000B0    |6C|65|64|5F|6D|6F|64|73|20|3D|20|6F|6C|64|5F|    led_mods.=.old_
000000C0    |6D|6F|64|73|2E|73|65|6C|65|63|74|7B|7C|6D|6F|    mods.select{|mo
000000D0    |64|7C|20|6D|6F|64|2E|73|74|61|72|74|5F|77|69|    d|.mod.start_wi
000000E0    |74|68|3F|20|22|2B|22|7D|0D|0A|0D|0A|75|6E|69|    th?."+"}....uni
000000F0    |71|75|65|5F|6D|6F|64|73|20|3D|20|65|6E|61|62|    que_mods.=.enab
00000100    |6C|65|64|5F|6D|6F|64|73|2E|73|65|6C|65|63|74|    led_mods.select
00000110    |7B|7C|6D|6F|64|7C|20|21|6E|65|77|5F|6D|6F|64|    {|mod|.!new_mod
00000120    |73|2E|69|6E|63|6C|75|64|65|3F|20|6D|6F|64|7D|    s.include?.mod}
00000130    |0D|0A|70|75|74|73|20|75|6E|69|71|75|65|5F|6D|    ..puts.unique_m
00000140    |6F|64|73|0D|0A|0D|0A|0D|0A|                      ods......
```
