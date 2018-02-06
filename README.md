# Cordova-sqlite-evcore-free-dependencies

AUTHOR: Christopher J. Brody

LICENSE: GPL v3 (http://www.gnu.org/licenses/gpl.txt) or commercial license options

Contains source and library (shared object) code built from:
- [litehelpers / Android-sqlite-evcore-native-driver-free](https://github.com/litehelpers/Android-sqlite-evcore-native-driver-free) - GPL v3 or commercial license options
- [SQLite (sqlite.org)](https://sqlite.org/) - public domain

This project provides the following dependencies needed to build Cordova SQLite evcore plugin versions:
- `sqlite3.h`, `sqlite3.c` - SQLite `3.15.2` amalgamation needed to build iOS and Windows versions
- `libs` - Android-sqlite-evcore-native-driver-free NDK libraries built with SQLite `3.15.2` amalgamation with the following option flags:
   - `-DSQLITE_TEMP_STORE=2`
   - `-DSQLITE_THREADSAFE=2`
   - `-DSQLITE_ENABLE_FTS3`
   - `-DSQLITE_ENABLE_FTS3_PARENTHESIS`
   - `-DSQLITE_ENABLE_FTS4`
   - `-DSQLITE_ENABLE_RTREE`
