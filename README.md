### link heroku [rest-api](https://limitless-island-91595.herokuapp.com/)

# rest-api
REST API with MVC architecture

## REST API
List of basic routes:

Route | HTTP | Descripton
--- | --- | ---
/api/hello?name={name} | GET | Print hello, {name} !

List of user routes:


Route | HTTP | Description
---|---|---|
/api/users|GET|Get all the users
/api/users/:id|GET| Get a single user
/api/users|POST|Create a user
/api/users/:id|DELETE| Delete a user
/api/users/:id|PUT  |Update a user with new info
/api/users/:id|PATCH|pdate a user with specific new info

list of filter routes :

Route |HTTP| Description
----|----|----|
/api/users?name="{name}"|GET|Get {name} match in users
/api/users?name="{na}"|GET|Get {na} like in users

## Usage
With only npm:
```
npm install.
npm start.
npm run dev.```

Access the website via `http://localhost:3000` or API via `htttp://localhost:3000/api.`
