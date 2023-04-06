# Hibera Website

This project was generated with [Firebase CLI](https://github.com/firebase/firebase-tools) version 11.21.0.


## First time using Firebase

These are the steps that should be taken when cloning a project for the first time with firebase.


### Firebase Tools

Run `npm install -g firebase-tool` if you do not have Firebase installed on your system.
(For MacOS users, you can also run `curl -sl https://firebase.tools | bash`)

### Login

Run `firebase login` to login the Google account that has gotten acces to the Firebase project(s).

### Check

Run `firebase projects:list` to see if you have access to the right project(s)

### Deploy

Whilst in the root of the poject, run `firebase deploy` to deploy the example website.


## Setting up a new firebase project

These are the steps to follow when creating a new firebase project.

### Firebase with Angular CLI

Run `firebase experiments:enable webframeworks`. This will make sure our Angular root file is the one that will be deployed.

### Initialise

Run `firebase init hosting` to initialise project. After you have run the command, there will be a couple of questions to answer. Depending on the need of the client, we will answer accordingly.

### Deploy preview

run `firebase hosting:channel:deploy [CHANNEL_ID]` to deploy the example website. Replace `[CHANNEL_ID]` with a string with no spaces. This ID will be used to construct the preview url associated with the preview channel.

### Deploy website
Run `firebase deploy` to deploy the website. (Only do this in production branch and when all is tested and well)

## Further help

To get more help on the Firebase CLI use `firebase help` or go check out the [Firebase CLI Overview and Command Reference](https://firebase.google.com/docs/cli) page.
