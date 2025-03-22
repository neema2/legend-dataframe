# Legend DataFrames

A DSL in Pure language for modeling SELECT statements that work with both Snowflake and DuckDB.

## Overview

This project implements a Domain Specific Language (DSL) in Pure language for modeling SQL SELECT statements that can be executed against both Snowflake and DuckDB databases. The DSL provides a unified interface for writing queries that can be translated to the appropriate SQL syntax for each database system.

## Features

- Model SELECT statements in Pure language
- Support for common SQL operations (filtering, grouping, aggregation, etc.)
- Compatible with both Snowflake and DuckDB
- Automatic SQL generation for the target database

## Project Structure

```
legend-dataframe/
├── src/
│   ├── main/
│   │   └── resources/
│   │       └── pure/
│   │           └── dsl/
│   │               ├── dataframe.pure       # Core DSL definitions
│   │               ├── snowflake.pure       # Snowflake-specific implementations
│   │               └── duckdb.pure          # DuckDB-specific implementations
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
