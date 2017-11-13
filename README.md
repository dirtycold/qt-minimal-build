# qt-minimal-build

Update: 2017-11-13

Several Qt build configurations

# Configurations

|Name                                     |Purpose|
|---                                      |---|
|qt_static-msvc                           |Qt static build script for MSVC|
|qt-mingw                                 |Qt build script for MinGW|
|qt_minimal-mingw                         |Qt minimal build script for MinGW|
|qt_minimal-mingw-with-serial-and-sensor  |Qt minimal build script for MinGW with Serial port/Serial bus/Sensor support|

# Minimal Build

## Features:

* QtCore
* QtGui
* QtWidgets
* QtNetwork (with OpenSSL linked in)
* QtSql (with only sqlite support)

## Known Issues

* *static* build is MSVC only
* *minimal* build doesn't contain QtConcurrent and QtXml feature from QtCore
* There is no obvious way to skip QtPrintSupport feature

