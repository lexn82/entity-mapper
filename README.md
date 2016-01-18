# entity-mapper [![Build Status](https://travis-ci.org/PagerDuty/entity-mapper.svg)](https://travis-ci.org/PagerDuty/entity-mapper)

This is an open source project!

## Description

Entity-mapper is a simple API for writing annotated classes into mutation batch, and converting query results back into class instances. Entity-mapper API is database and driver agnostic.

Key features:
 * Native handling of Scala Options
 * Nested entities
 * STI style inheritance support

## Installation

This library is published to PagerDuty Bintray OSS Maven repository:
```scala
resolvers += "bintray-pagerduty-oss-maven" at "https://dl.bintray.com/pagerduty/oss-maven"
```

Adding the dependency to your SBT build file:
```scala
libraryDependencies += "com.pagerduty" %% "entity-mapper" % "0.5.0"
```

## Contact

This library is primarily maintained by the Core Team at PagerDuty.

## Contributing

Contributions are welcome in the form of pull-requests based on the master branch.

We ask that your changes are consistently formatted as the rest of the code in this repository, and also that any changes are covered by unit tests.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)
