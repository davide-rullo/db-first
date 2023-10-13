# Car Dealer Database

## Table name

- cars

## Table columns

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- brand | VARCHAR(30), NOT NULL
- model | VARCHAR(30), NOT NULL
- price | DECIMAL(7, 2), NULL
- registration_year | YEAR, NULL
- mileage | DECIMAL(7, 2), NULL
- color | VARCHAR(30), NULL
- fuel_type | VARCHAR(30), NOT NULL
- engine | VARCHAR(50), NULL
- cover_image | VARCHAR(255), NULL
- note | TEXT, NULL
- is_available | TINYINT, DEFAULT(0)
- location | VARCHAR(50), NULL