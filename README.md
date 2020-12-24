# family-recipes
Attempt to modernize the family's recipe book which currently exists on Google Drive. New web app will sync with the existing google doc repository. 

Trello: https://trello.com/b/4WNsAfl1/recipe-book

## Database
host: family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com <br>
port: 5432 <br>
db-name: family_recipes <br>
username: postgres <br>
password: ha! nice try, loser. <br>

postgraphql connection string: 'postgres://<username>:<password>@<host>:<port>/<db-name>'
full postgraphile run command: postgraphile -c 'postgres://postgres:<password>@family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com:5432/family_recipes' --schema 'test_schema' --dynamic-json

local psql connection command: psql --host=family-recipes.cutdnpzgz2gb.us-west-2.rds.amazonaws.com --port 5432 --username=postgres --password --dbname-family_recipes
