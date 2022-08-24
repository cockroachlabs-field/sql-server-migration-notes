# sql-server-migration-notes

## Data Type Mapping
| SQL Server Type  | CRDB Type  |
| :------------ |:---------------|
| bigint | bigint
| numeric | numeric
| bit | boolean
| smallint | smallint
| decimal | decimal
| smallmoney | decimal(9,2)
| int | int
| tinyint | smallint
| money | decimal(9,2)
| double precision | double precision
| float | float
| real | real
| date | date
| datetimeoffset | timestamp with time zone, timestamptz
| datetime | timestamp(3)
| datetime2 | timestamp
| smalldatetime | timestamp(0)
| time | time
| char | char
| varchar | varchar
| varchar(max) | text
| text | text
| nchar | char
| nvarchar | varchar
| nvarchar(max) | text
| ntext | text
| binary | bytea
| varbinary | bytea
| image | bytea
| uniqueidentifier | uuid
| xml | jsonb
| Spatial Geometry Types | geometry
| Spatial Geography Types | geography
| cursor | n/a
| rowversion | n/a
| hierarchyid | n/a
| sql_variant | n/a
| table | n/a

