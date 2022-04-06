![](doc/dlanding.png)

Digits is a application that users can use to:
  * Register an account
  * Create and manage contacts
  * Add timesamped notes to those contacts

## Installation

First, [install Meteor](https://www.meteor.com/install).

Second, [download Digits](https://github.com/jiahuiliao/digits) by first requesting access.

Third, cd into the app/ directory and install third party libraries with:

```
$ meteor npm install
```

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/app/package.json):

```
$ meteor npm run start
```

Once you run the app, you might see an output similar to the below:

```

PS C:\Users\cette\Documents\GitHub\digits\app> meteor npm restart

> meteor-application-template-react@ start C:\Users\cette\Documents\GitHub\digits\app 
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings 
../config/settings.development.json

[[[[[ C:\Users\cette\Documents\GitHub\digits\app ]]]]]

=> Started proxy.
=> Started MongoDB.                           
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.

```

Additionally, you are able to run over the code to view any errors by running ESLint.

```
meteor npm run lint
```

## Walkthrough

### Landing
![](doc/dlanding.png)


### Signing up

### Signing in

### User home page

### List Contacts

### Edit Contacts

### Admin

