# StarSnowflakeSchemas
Repository focused on demonstrating and implementing Star and Snowflake schemas

## Overview
This repository explores **Star** and **Snowflake** schemas, two of the most popular data modeling techniques used in data warehousing. These schemas help in organizing and optimizing data for business intelligence and analytics purposes.

- **Star Schema**: A **denormalized** structure where fact tables(central) are surrounded by dimension tables in a star-like pattern. It's straightforward and performs well for simpler queries.
- **Snowflake Schema**: A more **normalized** form of the star schema, where dimension tables are further broken down into related tables (achieve it by normalizing the data to the third normal form - 3NF), resembling a snowflake. This schema optimizes storage at the cost of query complexity.

## Contents
- `diagrams/`: Schema diagrams showing the structure of both star and snowflake schemas.


## Why Use Star and Snowflake Schemas?

### Star Schema
- **Simplicity**: Easier to understand and query, with a flat structure.
- **Performance**: Optimized for fast query performance in BI tools.

### Snowflake Schema
- **Normalization**: Saves storage space by normalizing dimension data.
- **Flexibility**: More flexible for complex reporting and querying needs.


## Diagrams
- Star Schema Diagram:
   ![Screenshot 2024-10-22 121340](https://github.com/user-attachments/assets/5ec99c24-4a36-4899-9c95-f6cf280cc5e2)


- Snowflake Schema Diagram:
  ![Screenshot 2024-10-22 125150](https://github.com/user-attachments/assets/efcf796c-6828-4897-a0df-2c90cb854c24)

- Dashboard:
  ![Screenshot 2024-10-22 121409](https://github.com/user-attachments/assets/f1bb9018-e9eb-442d-96f4-2b9694aee486)

## License
This repository is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For questions or collaboration, reach out to:
- **Derek Prates**
- Email: yderekbomfim@hotmail.com
