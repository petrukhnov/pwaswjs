# Original project

https://github.com/NastyaSmirnova/PWCat

# What is different

* newer version of angular: 6.1
* guide how to  deploy to firebase

# initial setup

* install nodejs: nodejs.org , latest was 10.8.0
* open project dir and install angular tools: npm install -g @angular/cli
* npm installnpm install
* ng serve
* http://localhost:4200/

# deploy to firebase

https://firebase.google.com/docs/hosting/

Deploy to Firebase

* build app for production: ng build --prod

* Create a Firebase account at https://firebase.google.com/console/
* Install the Firebase tools via npm: npm install -g firebase-tools

* Create a new app at https://firebase.google.com/console/
* If you haven't recently signed in to the Firebase tools, update your credentials: firebase login
* Initialize your app, and provide the directory (likely work) where your completed app lives: firebase init ; Select only Hosting ; select dist as sources
* modify .firebaserc and put your project name there
* https://console.firebase.google.com : click develop/database and create database
* Finally, deploy the app to Firebase: firebase deploy
* Celebrate. You're done! Your app will be deployed to the domain: https://YOUR-FIREBASE-APP.firebaseapp.com


# demo

https://pwaswjs.firebaseapp.com/


