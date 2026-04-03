my-db-bundles/
├── databricks.yml          # Root bundle config
├── README.md
├── resources/              # Shared resources
│   └── sql-warehouses.yml  # Shared SQL warehouse
└── projects/
    └── linkedin/
        └── resources/
            ├── jobs.yml        # The daily ingest job
            ├── pipelines.yml   # The declarative pipeline
            ├── schemas.yml     # Bronze, silver, gold schemas
            └── volumes.yml     # Landing volume
