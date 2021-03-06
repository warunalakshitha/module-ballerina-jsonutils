Ballerina JsonUtils Library
===================

[![Build Master Branch](https://github.com/ballerina-platform/module-ballerina-jsonutils/workflows/Build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-jsonutils/actions?query=workflow%3ABuild%22)
[![Daily build](https://github.com/ballerina-platform/module-ballerina-jsonutils/workflows/Daily%20build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-jsonutils/actions?query=workflow%3ADaily+Build%22)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-jsonutils.svg)](https://github.com/ballerina-platform/module-ballerina-jsonutils/commits/master)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The Jsonutils library is one of the standard library modules of the<a target="_blank" href="https://ballerina.io/"> Ballerina</a> language.

This module provides utility functions to manipulate the built-in `json` data type. It provides APIs to convert an `xml` to a `json` or convert a `table` to a `json`.

## Building from the Source

1. Download and install Java SE Development Kit (JDK) version 8 (from one of the following locations).

   * [Oracle](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
   
   * [OpenJDK](http://openjdk.java.net/install/index.html)
   
        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.

### Building the Source

Execute the commands below to build from source.

1. To build the library:

        ./gradlew clean build

2. To run the integration tests:

        ./gradlew clean test

3. To build the module without the tests:

        ./gradlew clean build -x test

4. To debug the tests:

        ./gradlew clean build -Pdebug=<port>

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

You can also check for [open issues](https://github.com/ballerina-platform/module-ballerina-jsonutils/issues) that interest you. We look forward to receiving your contributions.

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All the contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss the code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
