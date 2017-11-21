# qt-minimal-build

Update: 2017-11-13

Several Qt build configurations

# Configurations

|Name                                     |Purpose|
|---                                      |---|
|qt_static-msvc                           |Qt static build script for MSVC|
|qt_static-mingw                          |Qt static build script for MinGW|
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

