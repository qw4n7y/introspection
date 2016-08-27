## PgBouncer

https://pgbouncer.github.io/
Lightweight connection pooler for PostgreSQL

## Cases of interest

* Nullable columns in unique indexes. As NULL != NULL it would not match same record sets as equal. Use default values or COALESCE function as column source for workaround.
