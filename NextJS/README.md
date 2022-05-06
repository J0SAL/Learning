- ```npx create-next-app```
  create Next App

- ```yarn dev```
  Starts the development server.

- ```yarn build```
  Builds the app for production.

- ```yarn start```
  Runs the built app in production mode.

- [Documentation Link](https://nextjs.org/docs)

- in pages folder

  - api : used to create api's
  - \_app : to create layout
  - index : file server on localhost:3000

- ```yarn dev``` ->
  - \_app.js builds and Componenets are matched
  - first file to exevute is index.js

- ### Routing!

  <img src="https://user-images.githubusercontent.com/52382282/167026647-7f6996d8-97c2-4619-99c1-a125b27fd5d7.JPG" alt="drawing" width="800"/>

- ### Pre-rendering!

  <img src="https://user-images.githubusercontent.com/52382282/167026666-01f8cfe9-8212-41f5-8a43-4368583131f2.JPG" alt="drawing" width="800"/>  
  <img src="https://user-images.githubusercontent.com/52382282/167115162-279107ec-d0ab-4c22-a4cb-3bb9e0162578.png" alt="drawing" width="800"/>
  
- ##Pre-rendering in NextJS is of 2 types: 
  - Static generation - 
    - HTML with all content of webpage is generated in advance when you build your app
      1. Static pages without data
      2. Static pages with data
  - server side rendering
