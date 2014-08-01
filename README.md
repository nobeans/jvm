# JVM the Java enVironment Manager

JVM is a tool for managing parallel Versions of multiple JDK.
It provides a convenient command line interface for switching and listing Candidates.
Notice that you must use an official JDK installer because it doesn't support installing JDK.

JVM was inspired by the [GVM](http://gvmtool.net/).


## Demo

![demo](./jvm-demo.gif)


## Requirements

* Mac only (currentyly some paths are specialized for Mac)
    - `JAVA_HOME=/Library/Java/JavaVirtualMachines/current`
    - You can cutomize it by editing `jvm` script file directly.
* Java SDKs
    - You must install them by an official installer.


## Installation

* Copy the `jvm` script to your `bin` directory


## Commands

* `list` / `ls` - Show list of installed JVM versions
* `default` / `d` - Set current JVM version
    - To replace the symbolic link of `/Library/Java/JavaVirtualMachines/current`

## License

Apache License, Version 2.0

