# test

a [Sails](http://sailsjs.org) application

steps to start the api-

in CMD

`

npm install
sails lift

`

basic routes for authentication are:

* http://localhost:1337/login
* http://localhost:1337/signup

until passing the token in header as the Authentication ------ (Bearer TOKEN_HERE) access won't be granted by the api.

then simple routes like

`
http://localhost:1337/user
http://localhost:1337/user/create
`
will work

#important -
your MySQL server should be up and running to work with the API.
DB name is 'sltest'

use this link to understand more about the authentication done in the project- https://github.com/saviogl/sails-hook-jwt-auth
