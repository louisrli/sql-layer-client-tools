# FoundationDB SQL Layer Client Tools

## Overview

Client-side tools for interacting with
[FoundationDB SQL Layer](https://github.com/foundationdb/sql-layer).


## Programs

### fdbsqldump

A command line tool for saving the contents of one or more schemas to a `sql`
file.

See [fdbsqldump docs](https://foundationdb.com/layers/sql/Admin/backup.html#fdbsqldump-command-line-tool)
for more information.

### fdbsqlload

A command line tool for loading the contents of a `csv`, `mysqldump` or
generic `sql` file into the database.

See [fdbsqlload docs](https://foundationdb.com/layers/sql/Admin/backup.html#fdbsqlload-command-line-tool)
for more information.


## Running Tests

FoundationDB SQL Layer must be installed and running on the local machine for tests to use.

