Console 64
==========

This simple project is supposed to expose an emulation of the Commodore 64
in a UNIX console, just for the lolz.

Status
------

Simple BASIC commands should work. There is some stub support for loading/saving
BASIC programs, but it is not complete.

Docs
----
A bit of C64 documentation can be found in the ```docs/``` directory. The annotated
ROM disassembly is particularly useful. Thanks Marko Makela!

Example
-------
```
willy@Minene console64 master$ python console64.py

    **** COMMODORE 64 BASIC V2 ****

 64K RAM SYSTEM  38911 BASIC BYTES FREE

READY.
10 PRINT "DIO"
20 PRINT " CANE"
30 PRINT "  VAFFANCULO"
```
```
LIST

10 PRINT "DIO"
20 PRINT " CANE"
30 PRINT "  VAFFANCULO"
READY.
```

```
30
```
```
LIST

10 PRINT "DIO"
20 PRINT " CANE"
READY.
```
```
DIO
CANE
 VAFFANCULO

READY.
```
