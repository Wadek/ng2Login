# basicLogin with AuthO

Install the dependencies.

```bash
npm install
```

Before you run the app, you'll need to enter the AuthO credentials in .env
 1) create .env file at project root.
 2) enter the following
 	```bash
 	AUTH0_CLIENT_ID= ID
	AUTH0_DOMAIN= domain
	AUTH0_CLIENT_SECRET= secret
 	```
 3) you can find the credentials on clack
	
Run the app.

```bash
npm start
```

The app will be served at `localhost:3000`. You have to use localhost:3000 or you will not be able to login.

login by either creating a custom account or use gmail.
