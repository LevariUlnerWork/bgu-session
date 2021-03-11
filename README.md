# CI/CD Workshop - Pokedex 

[![Build Status](https://travis-ci.com/ofirattia/bgu-session.svg?branch=master)](https://travis-ci.com/ofirattia/bgu-session)

## ACCESS TOKEN - TRAVIS
Please make sure you are going to https://github.com/settings/tokens and create an ACCESS TOKEN for Travis, this token is being used for pushing and creating releases to your repoistory.
The access token should be set after that on Travis settings as ENV Variable on https://travis-ci.com/github/YOUR_USER_NAME/YOUR_REPOSITORY/settings, the name of the variable should be GITHUB_TOKEN since we are using it in the .travis.yml file in this project.
- Please note that its not a must for this session, but you can do it to understand how you can use the travis for further activities.
 
List of pokemons on the basis of React + Redux 
 
## Available Scripts 
 
In the project directory, you can run:

### `npm start`   

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build` 
 
Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!


