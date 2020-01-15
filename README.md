# PushDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.12. It is a demo project designed for [technical article](https://medium.com/kabbage-engineering/angular-pwa-app-notification-using-firebase-cloud-messaging-d1b7bd171b98). Please read and follow that article to see how to play with demo

## Run PWA locally
1. Please update the content of [environment.prod.ts](src/environments/environment.prod.ts) to your own firebase setting
2. Install `http-server-spa` globally: `npm install -g http-server-spa@1.3.0`, you will only need to run this once.
3. Build production module with source map:`ng build --prod --source-map`
4. Serve your application using `http-server-spa dist/PushDemo/ index.html 18080` (I used 18080 port, you can use any free port you are using), visit http://localhost:18080/.
