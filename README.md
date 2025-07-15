# Database-Systems

**Brewery Analytical Database – SQL (PostgreSQL)**

- Made new PostgreSQL types to group beer information together and wrote functions that take input (like country or beer name) and return clean, structured results that are easy to use in other queries.
- **Built** 10+ modular SQL views by joining normalized tables (`breweries`, `beers`, `styles`, `ingredients`, `locations`) to extract insights like oldest breweries, missing beer styles, strongest barrel-aged beers, and most common ingredients.
- **Used** optimized SQL patterns (`JOIN`, `GROUP BY`, `EXCEPT`, `ORDER BY LIMIT`) to simplify query logic, reduce redundancy, and efficiently answer business questions without creating intermediate tables.
- **Ensured** clean, one-pass database loading by ordering view, type, and function definitions correctly, and handled missing location fields using `COALESCE` to avoid NULL-related failures in queries.

**Python and PostgreSQL Movie Database Query System**

- Built **5 Python scripts** that **recognised PostgreSQL code** to query IMDB movie data, handling over **1,000,000+ records.**
- Implemented **data extraction** and **transformation** to retrieve 200+ movies directed by specific people, countries of release, top-10 genres by year, actor roles, and cast lists by movie.
- Optimised **ETL** process with optional SQL views and PLpgSQL functions to enhance data retrieval and performance.
