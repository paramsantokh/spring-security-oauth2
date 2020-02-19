# Sign in using github/fb/google

This application shows how an application can authenticate users using github/fb/google authentication.

# URL

>http://localhost:8080 

Accessing above url will redirect to github/fb/google authorixzation page asking for authorize the user. 
Once user authorize, the page will be redirected to index.html, indicating oauth authenticated the user.

access token need to be set in application.yml file with clientId and clientSecret.
clientId and clientSecret can be retrieved by creating the app in developer.facebook.com or developer.github.com.
