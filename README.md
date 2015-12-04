## Impala/Hive SQL Pivot Example
### This example describes how Impala SQL can be used to pivot columns to rows and vice versa. 

Most relational databases such as Oracle and MS SQL provide some form of built in functions to pivot tables row values into column values and vice versa (See PIVOT/UNPIVOT functions in MS SQL and Oracle). 

Pivoting column values into rows is sometimes needed in order to provide a key-value based input by key to a downstream processor:


Pivoting multiple row values into a single row with multiple columns is usually needed to create line level reports that consolidate multiple key-value properties into a single row per primary key:


