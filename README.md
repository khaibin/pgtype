[![](https://godoc.org/github.com/khaibin/pgtype?status.svg)](https://godoc.org/github.com/khaibin/pgtype)

# pgtype

pgtype implements Go types for over 70 PostgreSQL types. pgtype is the type system underlying the
https://github.com/jackc/pgx PostgreSQL driver. These types support the binary format for enhanced performance with pgx.
They also support the database/sql `Scan` and `Value` interfaces and can be used with https://github.com/lib/pq.
