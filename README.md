# ATM-AttendanceTrackerManagement
This project contains three part
- Web Admin
- Mobile
- Backend



## Web Admin
Description: This is the web version where the super user can control their group and do admin stuff

### Tech
- [Node.js](https://nodejs.org/en) - A powerful runtime for javascript 
- [Angular](https://angular.dev/) - A framework to build web applications
- [Material Web (Material 3)](https://m3.material.io/) - A Design System that Google developed which widely used
- [NGRX](https://ngrx.io/) - A powerful tool for manage state in Angular

### How to run
This project requires [Node.js] v18+ and [Angular CLI](https://angular.dev/tools/cli) to run

Install the dependencies and devDependencies

```sh
cd DACNA-WebAdmin
npm i
```

Start the Angular project
```sh
ng s
```



## Mobile
Description: This is where a normal user check in and check out

### Tech
- [Node.js](https://nodejs.org/en) - A powerful runtime for javascript 
- [React Native](https://reactnative.dev/) - A framework to build modile apllication on multiple platforms
- [React Native Paper](https://reactnativepaper.com/) - A Design System follow Material Design on Mobile
- [React Native Camera Kit](https://github.com/teslamotors/react-native-camera-kit) - A toolkit for React Native app to use camera on mobile
- [Redux](https://redux.js.org/) - A powerful tool for manage state in React/React Native

### How to run
This project requires [Node.js] v18+

Install the dependencies and devDependencies

```sh
cd DACNA-Mobile
npm i
```

Currently this project only support Android

To build a Development Build, run command
```sh
npx expo run:android
```
or prebuild it and use [Android Studio](https://developer.android.com/studio) and install it on the phone
```sh
npx expo prebuild
```

Then we can start the project 

```sh
npm run start
```

Enter the uri and use



## Backend
Description: This is the server to serve Mobile and Web Admin

### Tech
- [Node.js](https://nodejs.org/en) - A powerful runtime for javascript 
- [Expressjs](https://expressjs.com/) - A lightweight library to make a backend server
- [MongoDB](https://www.mongodb.com/) - A NoSQL database, easy to use

### How to run
This project requires [Node.js] v18+

Install the dependencies and devDependencies

```sh
cd DACNA-Backend
npm i
```

And start the server

```sh
npm run dev
```
