# qt-minimal-build

Update: 2018-01-18

Several Qt build configurations

# Configurations

|Name                                     |Purpose|
|---                                      |---|
|qt_static-msvc                           |Qt static build script for MSVC|
|qt_static-mingw64                        |Qt static build script for MinGW(64bit)|
|qt_static-mingw32                        |Qt static build script for MinGW(32bit)|
|qt_minimal-mingw                         |Qt minimal build script for MinGW|
|qt_minimal-mingw-with-serial-and-sensor  |Qt minimal build script for MinGW with Serial port/Serial bus/Sensor support|

# Minimal Build

## Features:

* QtCore (without QtConcurrent/QtTest/QtXml feature)
* QtGui
* QtWidgets
* QtNetwork (with OpenSSL linked in)
* QtSql (with only sqlite support)

## Known Issues

* There is no obvious way to skip QtPrintSupport feature

