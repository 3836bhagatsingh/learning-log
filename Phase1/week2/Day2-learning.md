Day2 learning

#SQL

Inner join -> ON clause
Syntax -> table_name1 join table_name2 on join condition



#PYTHON

Nested structures = real-world JSON representation (API standard format)
Dict inside dict → hierarchical relationship (parent-child mapping)
List of dicts → one-to-many relationship (like table rows)
Most APIs return → combination of nested dict + list (deep nesting possible)
Access complexity increases with depth → key chaining required (a["b"]["c"])
Missing keys can break code → use .get() for safe extraction
Data is not analysis-ready → requires flattening (normalization step)
Flattening converts → nested → tabular (rows & columns)
Lists require → looping / explode (row duplication concept)
Dict keys → become column names after transformation
Deep nesting → multi-level schema extraction needed
Performance impact in pipelines → due to recursive parsing
Common in tools → PySpark (explode), Pandas (json_normalize)
Schema drift possible → API structure may change dynamically
Critical DE skill → parse → validate → flatten → load (ETL flow)



 



