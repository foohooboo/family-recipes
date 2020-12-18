# family-recipes
Attempt to modernize the family's recipe book which currently exists on Google Drive

## Database
host: family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com
port: 5432
db-name: family_recipes
username: postgres
password: ha! nice try, loser. It's something both judd and i know, in case judd gets involved

postgraphql connection string: 'postgres://<username>:<password>@<host>:<port>/<db-name>'
full postgraphile run command: postgraphile -c 'postgres://postgres:<password>@family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com:5432/family_recipes' --schema 'test_schema' --dynamic-json

local psql connection command: psql --host=family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com --port 5432 --username=postgres --password --dbname-family_recipes