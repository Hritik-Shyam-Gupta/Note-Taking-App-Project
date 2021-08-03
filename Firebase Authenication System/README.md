# Firebase Login System (ReactJS - Firebase)

Firebase login system is a simple, fully functioning user authentication application created using firebase auth and react.

### Features
* User registration and sign in with email & password
* User sign in with social accounts: Google, Facebook, & Twitter
* Stay signed in option
* Firestore initialization
* Client-side form error handling
* Password reset
* Email verification
* Modify email and/or password

### Technologies
* ReactJS (Context API/Hooks)
* Material UI/Core; Material UI/Lab
* React Router DOM
* Firebase - Auth - Firestore

## Start Project

##### `git clone {Repositry Link}`
##### `cd firebase-login-system`
##### `npm install`
##### `npm start`

## Important!

For the project to run, you need to apply your firebase project's SDK to local environment variables. To do so, we put the project's config info in the provided `.env` file.
Once finished, make sure your .env file (or whatever you rename it to) is included in your .gitignore file so your project's info isn't uploaded when you go to build and deploy the app.

### Firebase Setup

- Create a project(web) and a clouse firestore.
- Setup Sign-in method by enabling email/password, google, and github in Authentication tab.

### Environment Variables

- Add the following env variables to .env file

```
REACT_APP_API_KEY={apiKey}
REACT_APP_AUTH_DOMAIN={authDomain}
REACT_APP_DATABASE_URL={databaseUrl}
REACT_APP_PROJECT_ID={projectId}
REACT_APP_STORAGE_BUCKET={storageBucketURL}
REACT_APP_MESSAGING_SENDER_ID={messagingSenderId}
REACT_APP_APP_ID={appId}
```

Make sure to add "REACT*APP*" before variables if you use create-react-app.

- Install npm packages

```bash
npm install
```

- Start dev server

```bash
npm start
```

<br>


Now your project should be visible on your computer locally @ http://localhost:3000/
