# build-a-bot
Simple Vue.js application with a Node/Express API, based on the Pluralsight Vue Fundamentals course from Jim Cooper available here: https://www.pluralsight.com/courses/vuejs-fundamentals

To run in development mode:

1. Start a new console window and start the server:
```
cd server
npm start
```

2. Start another console window and run the WebPack dev server
```
cd client
npm run serve
Browse to http://localhost:8080
```

To build for production:
- In the client directory run
```npm run build```
- This will build a production build and place the output in the **/dist** directory
- Copy the **/dist** directory to the **/server** directory
- Restart the server if necessary
- Browse to ```http://localhost:8080```