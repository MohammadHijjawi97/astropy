Fixed ``write_parquet_votable`` wrongly reporting ``description`` as an invalid
metadata key when a column already has a description. Invalid metadata keys
now emit an ``AstropyUserWarning`` instead of being printed.
