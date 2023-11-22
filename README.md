# Docker_Database-Container
Set up a database container (e.g., MySQL or PostgreSQL) and connect it to a web application container while Ensuring data persistence.

For database use Postgres image and for web app - node image is used

>> volume mounting- volume is created automatically when doing volume mounting

Environmental variables format:

***There are 2 formats while writing environmental variables. those are.
environment:
  - POSTGRES_USER=your_user
  - POSTGRES_PASSWORD=your_password
  - POSTGRES_DB=your_database

or

environment:
  POSTGRES_USER: your_user
  POSTGRES_PASSWORD: your_password
  POSTGRES_DB: your_database
