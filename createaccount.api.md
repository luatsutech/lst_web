**`API Documentation for a user creating a new account`**

> domain/app/update/create_account.php

**`Parameters`** _(all of them are required)_

**firstname**: The string for the first name of the user

**lastname**: A string for the last name of the user

**email**: A string for the email of the user

**password**: A string for the password of the user

**sex**: A string for the sex of the user

**`Response`** 

There is no response, the user is then logged in once the account is successfully created

If the account is not successfully created, the user will be returned to the sign up page with an 
error message embedded in the url

If there is an internal server error, you will get nothing but the server will silently fail and 
you could possibly get a file 500 error in the javascript console