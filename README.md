# Netflix-clone Website:

https://netflix-clone-e9014.web.app/

The following project is built with ReactJs as front-end using TMDB API which is used to get the
movie details and firebase as backend and for deploying and hosting the production build app.

# Few CLI cmds ran during the project development:

## `cd netflix-clone/`

## `code .`

## `npm i react-youtube`

## `sudo npm i movie-trailer`

################################################################################

## `firebase login`

i Firebase optionally collects CLI usage and error reporting information to help improve our products. Data is collected in accordance with Google's privacy policy (https://policies.google.com/privacy) and is not used to identify you.

? Allow Firebase to collect CLI usage and error reporting information? Yes
i To change your data collection preference at any time, run `firebase logout` and log in again.

Visit this URL on this device to log in:

<!-- This is commented out. -->
<!--
https://accounts.google.com/o/oauth2/auth?client_id=563584335869-fgrhgmd47bqnekij5i8b5pr03ho849e6.apps.googleusercontent.com&scope=email%20openid%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloudplatformprojects.readonly%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Ffirebase%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloud-platform&response_type=code&state=507948042&redirect_uri=http%3A%2F%2Flocalhost%3A9005
-->

Waiting for authentication...

## ✔ Success! Logged in as abinash.behera04@gmail.com

################################################################################

## `firebase init`

     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

/Users/ab067240/Documents/projects/netflix-clone

? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, then Enter to confirm your choices. Hosting: Configure and deploy Firebas
e Hosting sites

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add,
but for now we'll just set up a default project.

? Please select an option: Use an existing project
? Select a default Firebase project for this directory: netflix-clone-e9014 (netflix-clone)
i Using project netflix-clone-e9014 (netflix-clone)

=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? build
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? Set up automatic builds and deploys with GitHub? No
? File build/index.html already exists. Overwrite? Yes
✔ Wrote build/index.html

i Writing configuration info to firebase.json...
i Writing project information to .firebaserc...

## ✔ Firebase initialization complete!

################################################################################

## `npm run build`

> netflix-clone@0.1.0 build /Users/ab067240/Documents/projects/netflix-clone
> react-scripts build

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

58.08 KB build/static/js/2.282a2202.chunk.js
1.88 KB build/static/js/main.6b63c459.chunk.js
1.57 KB build/static/js/3.65dcedc3.chunk.js
1.17 KB build/static/js/runtime-main.e32d6cae.js
898 B build/static/css/main.43d680b7.chunk.css

The project was built assuming it is hosted at /.
You can control this with the homepage field in your package.json.

The build folder is ready to be deployed.
You may serve it with a static server:

npm install -g serve
serve -s build

Find out more about deployment here:

## https://cra.link/deployment

################################################################################
Final step to Deploy:

## `firebase deploy`

Output:
$ firebase deploy

=== Deploying to 'netflix-clone-e9014'...

i deploying hosting
i hosting[netflix-clone-e9014]: beginning deploy...
i hosting[netflix-clone-e9014]: found 18 files in build
✔ hosting[netflix-clone-e9014]: file upload complete
i hosting[netflix-clone-e9014]: finalizing version...
✔ hosting[netflix-clone-e9014]: version finalized
i hosting[netflix-clone-e9014]: releasing new version...
✔ hosting[netflix-clone-e9014]: release complete

✔ Deploy complete!

Project Console: https://console.firebase.google.com/project/netflix-clone-e9014/overview
Hosting URL: https://netflix-clone-e9014.web.app

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
