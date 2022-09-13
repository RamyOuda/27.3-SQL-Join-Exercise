# 27.2 SQL Query Exercise

### To seed your database on Windows:

- Install the directory
  - Click the green "Code" button near the top-right
  - Click "Download Zip"
- Using the terminal, cd into the directory holding the .sql files
- Once in the correct directory, run the command:
  - "**psql -f seed_products.sql**"
  - **OR** if you have not set your system environment variables: "**psql -U postgres -f seed_products.sql**" and enter password

A new database with the 'products' table should be automatically created for you.
