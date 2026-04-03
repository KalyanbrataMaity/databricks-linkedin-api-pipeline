#### Project structure

my-db-bundles/
|-- databricks.yml  # Root budle config
|-- README.md
|-- resources/ # Shared resources
|   |__ sql-warehouses.yml # Shared SQl warehouse
|__ projects/
    |__ linedkin/
    |-- resources/
        |-- jobs.yml # The daily ingest job
        |-- pipelines.yml # The declarative Pipeline
        |-- schemas.yml # Bronze, silver, gold schemas
        |__ volumes.yml # Landing volume