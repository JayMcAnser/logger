[home](../README.md)

# Logger Revisions

## 2022-08-16 V0.11.0
- fix: absolute path in the logger

## 2022-04-14
- upd: update every thing with ncu

## 2020-10-28
- fix: throws error if unable to create directory 

## 2020-08-12
- fix: debug show empty message

version 0.10 - 20208-08-06
- level: debug
- transport.file: targetFile is full path to file
- isDebugActive
- options.debug to active the debugger
- level are limited to error, warn, info, debug
- rootDir use pipe to find a directory

version 0.9
- auto change transports to [transports]
- fix: empty message in super.log

version 0.4.0
- added toConsole property

version 0.3.2
- add the rootDirectoy to the WinstonLogger to define where the log files are written 
- added a pipe to connect multiple loggers
