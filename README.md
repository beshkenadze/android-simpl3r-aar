android-simpl3r-aar
========================

Android-simpl3r library built with gradle in aar format for usage with android gradle build system. 

How to use
=======================
Before you can get aar you should checkout [android-simpl3r](https://github.com/jgilfelt/android-simpl3r) submodule. Overall build process including build is straightforward:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew build uploadArchives
```
