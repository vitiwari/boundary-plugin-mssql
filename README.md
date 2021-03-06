# TrueSight Pulse Microsoft SQL Server Plugin

Collects metrics from Microsoft SQL Server instance using a subset of the SQL Server Performance Counters. 

### Prerequisites

- SQL Server 2008, 2012, 2014 OR 2016.

Multiple instances of SQL Server running on the same machine are supported: each instance will show up as a separate source on your TrueSight Pulse dashboard.

#### Supported OS

|     OS    | Linux | Windows | SmartOS | OS X |
|:----------|:-----:|:-------:|:-------:|:----:|
| Supported |   -   |    v    |    -    |   -  |

#### TrueSight Pulse Meter versions v4.2 or later

- To install new meter go to Settings->Installation or [see instructions](https://help.truesight.bmc.com/hc/en-us/sections/200634331-Installation).
- To upgrade the meter to the latest version - [see instructions](https://help.truesight.bmc.com/hc/en-us/articles/201573102-Upgrading-the-Boundary-Meter).

### Plugin Setup

None

### Plugin Configuration Fields

|Field Name     |Description                                                                       |
|:--------------|:---------------------------------------------------------------------------------|
|Source         |The source to display in the legend for the data                       |
|Poll Interval (ms)|The Poll Interval in milliseconds to poll for metrics |

### Metrics Collected

|Metric Name             |Description                                                   |
|:-----------------------|:-------------------------------------------------------------|
| MSSQL_ACTIVE_TEMP_TABLES | MSSQL - Active Temp Tables|
| MSSQL_USER_CONNECTIONS | MSSQL - User Connections|
| MSSQL_LOGICAL_CONNECTIONS |MSSQL - Logical Connections |
| MSSQL_TRANSACTIONS |MSSQL - Transactions |
| MSSQL_PROCESSES_BLOCKED |MSSQL -processes blocked |
| MSSQL_LOCK_TIMEOUTS | MSSQL - Lock Timeouts|
| MSSQL_LOCK_WAITS |MSSQL - Lock Waits |
| MSSQL_LOCK_WAIT_TIME_MS | MSSQL - Lock Wait Time (ms)|
| MSSQL_LOCK_AVERAGE_WAIT_TIME_MS | MSSQL - Lock Average Wait Time (ms) |
| MSSQL_LOCK_TIMEOUTS_GT0 | MSSQL - Lock Timeouts (>0)|
| MSSQL_PERCENT_LOG_USED | MSSQL - % Log Used|
| MSSQL_REPL_PENDING_XACTS | MSSQL - Replication Pending Transactions|
| MSSQL_COMPILATIONS | MSSQL - sql compilations/sec |
| MSSQL_PAGE_IO_LATCH_WAITS | MSSQL - IO Latch Waits |

### Dashboards

- MSSQL

### References

None
