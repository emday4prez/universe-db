# universe-db

Each table has specific columns to capture relevant attributes and relationships among objects. The tables utilize primary keys, foreign keys, and various data types to ensure data integrity and enable efficient querying.

## Usage

To use the "Universe" database, follow these steps:

1. Create a database named "universe" using the appropriate SQL command.
2. Connect to the "universe" database using your preferred database client or the appropriate command-line tool.
3. Execute the SQL statements provided in the "universe.sql" file to create the necessary tables and populate them with sample data.
4. You can now perform queries and operations on the database using SQL commands to retrieve, insert, update, or delete data as needed.

## Sample Queries

Here are some example queries you can run against the "Universe" database:

- Retrieve all galaxies: `SELECT * FROM galaxy;`
- Find all planets in a specific star system: `SELECT * FROM planet WHERE star_id = <star_id>;`
- Get details of a moon and its associated planet: `SELECT * FROM moon WHERE moon_id = <moon_id>;`
- Find nebulas with a certain age range: `SELECT * FROM nebula WHERE age_in_millions_of_years BETWEEN <min_age> AND <max_age>;`

Feel free to explore and modify the database schema and data to suit your specific needs.

## Credits

The "Universe" database was created by Emerson Day as a project for FreeCodeCamp.
