Single sign-on (SSO) is an identification method that enables users to log in to multiple applications and websites with one set of credentials.

This application allows users to login to all websites registered to the domain of IIT Jodhpur, using just a single login.

The user is authenticated using LDAP credentials and a cookie is issued and the user information is stored in the SSO database.
Thus allowing authentication through SSO only later on. The cookie generated is used to login the user to all websites registered with the SSO.

The application uses django rest framework for building the web API and dbsqlite3 as the database.

Tech Stack: Django, dbsqlite3, HTML/CSS
