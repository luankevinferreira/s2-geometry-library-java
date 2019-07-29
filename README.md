# About this repository
 [![Build Status](https://travis-ci.org/io-sgr/s2-geometry-library-java.svg?branch=master)](https://travis-ci.org/io-sgr/s2-geometry-library-java) [![codecov](https://codecov.io/gh/io-sgr/s2-geometry-library-java/branch/master/graph/badge.svg)](https://codecov.io/gh/io-sgr/s2-geometry-library-java)

This repository is forked from [s2-geometry-library-java](https://github.com/google/s2-geometry-library-java) which is originally hosted on [Google Code](https://code.google.com/archive/p/s2-geometry-library-java/). The last update was about 6 years ago, doesn't seem to be maintained.

This fork contains several updates:
* Support build with Maven.
* Removed Guava compile dependency make it easier to use on Android.
* Added proguard configuration.
* Released to Maven Central.

# How to use
* If you are using **Maven**, add denpendency in `pom.xml`:
  ```
  <dependency>
      <groupId>io.sgr</groupId>
      <artifactId>s2-geometry-library-java</artifactId>
      <version>1.0.0</version>
  </dependency>
  ```
* If you are using **Gradle**, add dependency in `build.gradle`:
  ```
  compile('io.sgr:s2-geometry-library-java:1.0.0')
  ```
