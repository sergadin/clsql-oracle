This module used to be a replacement for Oracle interface in CLSQL.
Original version of CLSQL is 6.4.1, (clsql-20130420-git from quicklisp)

Tested on Oracle instantclient 11.2

Changes made:
1) Fix a typo (?) in sql-stmt-exec that yields an error in (clsql:query ...)

TODO:
prepare/bind
