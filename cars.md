# table title

cars

## table structure
- id | SMALLINT, NOTNULL, UNIQUE, AUTOINCREMENT, PRIMARY_KEY
- brand_key | SMALLINT, NOTNULL
- model_key | TINYINT, NOTNULL
- model | VARCHAR(20), NULL
- images | VARCHAR(255), NULL
- VIN | VARCHAR(17), NULL, UNIQ
- external_color | VARCHAR(10), NULL
- internal_color | VARCHAR(10), NULL
- internal_material | VARCHAR(10), NULL
- price | MEDIUMINT, NULL
- km | MEDIUMINT, NULL
- year | YEAR, NULL
- description | TEXT, NULL
- engine_size | SMALLINT, NULL
- fuel | VARCHAR(10), NULL
- seats | TINYINT, NULL
- doors | TINYINT, NULL
- transmission | VARCHAR(10), NULL
- traction | VARCHAR(10), NULL
- power | SMALLINT, NULL
- emission_class | VARCHAR(2), NULL