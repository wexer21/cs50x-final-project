# cs50x-final-project

CassandraQB is an open source query builder for Apache Cassandra database.
It supports four basic operations. Select delete update and insert. It also supports batches
so you can do more that one operation per batch. once your batch is ok, you can execute it to
execute all generated queries for you. be careful that you can't use select operations in batches
otherwise you will recieve an error.

This query-builder is based on github.com/gocql/gocql package and it is written in golang language.
so check it out for more information and learn more about how does this query builder works.
