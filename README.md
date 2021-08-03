# Project Description!

This is a Summer-Internship 2021 Project of creating a Note Taking Web Application (An Evernote CLone) by the Students of Dayalbagh Educational Institute.

Evernote clone is a basic note taking application similar in functionality to Evernote.

### Features
* Create note
* Select note
* Modify note
* Delete note
* Notes organized by most recently updated
* Firestore initialization
* User note collection modification

### Technologies Stack
* ReactJS (Classes)
* React Quill Editor
* Material UI/Core
* React Router DOM
* Firebase - Auth - Firestore


# Evernote Clone (ReactJS - Firebase)

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Important!

For the project to run, you need to apply your firebase project's SDK to local environment variables. To do so, we put the project's config info in the provided `.env` file.
Once finished, make sure your .env file (or whatever you rename it to) is included in your .gitignore file so your project's info isn't uploaded when you go to build and deploy the app.

### Firebase Setup

- Create a project(web) and a cloud firestore Databse on Firebase in your account.
- Setup Sign-in method by enabling email/password in Authentication tab.

###First Step

- cd into the Evernote-editor directory

```bash
cd Evernote-editor/
```

Now Follow these steps to Start the Application on your Machine.


### Environment Variables

- Add the following env variables to .env file

```
REACT_APP_FIREBASE_API_KEY = <your api key>
REACT_APP_FIREBASE_AUTH_DOMAIN = <your auth domain>
REACT_APP_FIREBASE_PROJECT_ID = <your project id>
REACT_APP_FIREBASE_STORAGE_BUCKET = <your storage bucket>
REACT_APP_FIREBASE_MESSAGING_SENDER_ID = <your messaging sender id>
REACT_APP_FIREBASE_APP_ID = <your app id>
REACT_APP_FIREBASE_MEASUREMENT_ID = <your measurement id>
```

Make sure to add "REACT*APP*" before variables if you use create-react-app.

- Install npm packages

```bash
npm install
```

- Install Other Dependencies

```bash
npm install react-quill
npm install @material-ui/core
npm install @material-ui/icons
```

- Install Firebase packages

```bash
npm install firebase
```

- Start dev server

```bash
npm start
```

<br>


Now your project should be visible on your computer locally @ http://localhost:3000/

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
