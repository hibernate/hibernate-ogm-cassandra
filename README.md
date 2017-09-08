# Hibernate OGM Cassandra

*Version: 5.2.0.Alpha1 - 08-09-2017*

## Description

This project integrates [Hibernate OGM](http://hibernate.org/ogm/) with [Apache Cassandra](http://cassandra.apache.org/).

For running the tests in the _cassandra_ module an installed Cassandra server is required. Specify its host name by
setting the environment variable `CASSANDRA_HOSTNAME` prior to running the test suite:

    export CASSANDRA_HOSTNAME=cassandra-machine

If this variable is not set, the _cassandra_ module still will be compiled and packaged but the tests will be skipped.
If needed, the port to connect to can be configured through the environment variable `CASSANDRA_PORT`.

## License

This software and its documentation are distributed under the terms of the
FSF Lesser Gnu Public License (see license.txt).
