# Create React App as PWA
This app is based on the create react app v5 and the PWA template. It was created like this:
`npx create-react-app create-react-app-pwa --template cra-template-pwa`

Official docu: https://create-react-app.dev/docs/making-a-progressive-web-app/

# Installation
npm install

# Development
npm run start

# Running as PWA
To run the app as PWA, which includes the service worker you will reqiure a server for static files. It is recommended to use `serve`, see https://create-react-app.dev/docs/deployment.

Build the app: `npm run build`.

Install the serve server: `npm install -g serve`.

Run your app `serve -s build`.


When everything works open your browser at http://localhost:3000 and you will not only see the app itself but also the following `console log` message:
```
This web app is being served cache-first by a service worker. To learn more, visit https://cra.link/PWA
```
Success!