# ioutil-java
IO utility library for Java

## Usage

There are 2 methods in this library.

- FileUtils.contentEquals(File firstFile, File secondFile, long offset, long length)
- IOUtils.contentEquals(InputSteam firstInput, InputStream secondInput, long offset, long length)

These are natural extension from Apache commons IO to add offset and length to be compared.
If you want to compare an entire content of both file, you can use commons-io.

## Build

IO utility library for java uses Gradle for build system.

```
$ gradle build
```

You will find archive files at

```
build/distributions
```

## Contribution

As usual of other projects hosted on GitHub, this project also welcome
forking source and send modification as a Pull Request.
It is recommended to post an issue before sending a patch.


## Copyrights and License

Copyright (C) 2016 Hiroshi Miura

This program distributed under Apache 2.0 license.