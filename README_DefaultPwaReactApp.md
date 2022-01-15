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