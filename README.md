# oracle-instantclient
Continuous Integration Docker pipeline support for Oracle libraries

Note that [node-oracledb](https://github.com/oracle/node-oracledb) doesn't package everything it needs to execute at runtime. The [Oracle Instant Client](https://www.oracle.com/technetwork/topics/intel-macsoft-096467.html) libraries are also needed for basic connectivity to an Oracle database instance. Docker build pipelines require access to all libraries to be used on a production image, and the Oracle site where these are hosted is behind a login wall. 
