# Default PWA React App

## Create project folders
- mkdir client server

## Client (React Js)
- npx create-react-app ./
- npm i react-router-dom 
- npm i bootstrap react-bootstrap

## Server (Node Js)
- npm i express dotenv cors mysql axios
- mkdir controllers middleware public routes services
- touch server.js .env .gitignore
- git init (Git repository in /Users/belaf./Library/Mobile Documents/com~apple~CloudDocs/04_HtDocs/04_React/default_pwa_react_app/server/.git/)
- ? cookie-parser web-push jsonwebtoken body-parser

## Video
- [React 2021](https://www.youtube.com/watch?v=UtP0h4x_Zxs&list=PLyuRouwmQCjmMfs-HOsDGoaN6JiYrC6Ms&index=6)

## PWA React app description
- [Create React App](https://create-react-app.dev/docs/making-a-progressive-web-app)
- [Git](https://github.com/AnasOnGit/react-yt-downloader-codestick)
- npx create-react-app my-app --template cra-template-pwa
- service-worker.js
- serviceWorkerRegistration.js
- index.js
    - import * as serviceWorkerRegistration from './serviceWorkerRegistration'
    - serviceWorkerRegistration.register()
- package.json
    - "workbox-background-sync": "^5.1.3",
    - "workbox-broadcast-update": "^5.1.3",
    - "workbox-cacheable-response": "^5.1.3",
    - "workbox-core": "^5.1.3",
    - "workbox-expiration": "^5.1.3",
    - "workbox-google-analytics": "^5.1.3",
    - "workbox-navigation-preload": "^5.1.3",
    - "workbox-precaching": "^5.1.3",
    - "workbox-range-requests": "^5.1.3",
    - "workbox-routing": "^5.1.3",
    - "workbox-strategies": "^5.1.3",
    - "workbox-streams": "^5.1.3"

## Deploy the application on
- heroku
- netlify
- [03:28:38 Deployment](https://www.youtube.com/watch?v=MJzbJQLGehs&t=45s)
- [git](https://github.com/adrianhajdin/project_medical_pager_chat/blob/master/client/src/components/Auth.jsx)

## PWA Manifest JSON logos
- DOCS [PWA React](https://www.youtube.com/watch?v=RvEEZLxiAlQ)
- logo192.png, logo256.png, logo384.png, logo512.png
- src, size. type
- maskable.png  196x196[maskable icon](https://maskable.app/editor)  //  ios icon
    - "purpose": "any maskable"
    - size: 196x196
    - "type": "image/png"