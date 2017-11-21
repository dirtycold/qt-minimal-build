%QTDIR%\qtbase\mkspecs\win32-g++\qmake.conf
---

```
QMAKE_LFLAGS = -static -static-libgcc
```

%QTDIR%\qtbase\qmake\Makefile.win32 
---

```
LFLAGS = -static -static-libgcc
```