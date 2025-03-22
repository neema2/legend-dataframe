# Legend DataFrames

A DSL in Pure language for modeling SELECT statements that work with Snowflake, DuckDB, BigQuery, and Databricks.

## Overview

This project implements a Domain Specific Language (DSL) in Pure language for modeling SQL SELECT statements that can be executed against Snowflake, DuckDB, BigQuery, and Databricks databases. The DSL provides a unified interface for writing queries that can be translated to the appropriate SQL syntax for each database system.

## Features

- Model SELECT statements in Pure language
- Support for common SQL operations (filtering, grouping, aggregation, etc.)
- Compatible with Snowflake, DuckDB, BigQuery, and Databricks
- Automatic SQL generation for the target database
- Support for database-specific features (e.g., Databricks QUALIFY and CLUSTER BY clauses)

## Project Structure

```
legend-dataframe/
├── src/
│   ├── main/
│   │   └── resources/
│   │       └── pure/
│   │           └── dsl/
│   │               ├── dataframe/
│   │               │   └── dataframe.pure   # Core DSL definitions
│   │               ├── snowflake/
│   │               │   └── snowflake.pure   # Snowflake-specific implementations
│   │               ├── duckdb/
│   │               │   └── duckdb.pure      # DuckDB-specific implementations
│   │               ├── bigquery/
│   │               │   └── bigquery.pure    # BigQuery-specific implementations
│   │               └── databricks/
│   │                   └── databricks.pure  # Databricks-specific implementations
│   └── test/
│       └── resources/
│           └── pure/
│               └── dsl/
│                   └── tests/               # Test cases
└── README.md
```

## Usage

TBD

## License

TBD
