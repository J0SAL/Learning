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

  <img src="https://user-images.githubusercontent.com/52382282/167626929-b79ecfc9-35a1-456c-b1e2-d80c06b24489.png" alt="drawing" width="800"/>  
  <img src="https://user-images.githubusercontent.com/52382282/167026666-01f8cfe9-8212-41f5-8a43-4368583131f2.JPG" alt="drawing" width="800"/>  
  <img src="https://user-images.githubusercontent.com/52382282/167115162-279107ec-d0ab-4c22-a4cb-3bb9e0162578.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167627439-c9230883-eda3-4b5d-b3ba-6610fd923adb.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167628018-91833eac-f1ee-45c9-9c60-6bd4ac0bebf3.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167628080-c796b349-8573-435b-9410-406941b730b8.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167648563-6b14fa7b-140d-4a98-a8d8-2bd9a67b99a2.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167648621-6fdc2a62-85f3-4ba6-a9cd-1116b843a1c7.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/167810809-fc71dbc5-b8bd-4a25-a839-96e3c3ecf49e.png" alt="drawing" width="800"/>
    
  - ### mention possible values of pages that are to be dynamically generated using getStaticPaths()
  - getStaticPaths fallback : [false , true, 'blocking'] 
  - 
  <img src="https://user-images.githubusercontent.com/52382282/172065486-7511fae0-8de6-4cb6-a786-8bd75c5c95b3.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172065519-24da3c7e-dc18-4a1f-afba-4b22f6eba044.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172065762-ed49fc8c-d12e-401a-8223-ee622ac061e5.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172066141-385465c2-31ad-48ca-bae0-2d244b3110ef.png" alt="drawing" width="800"/>
  
  - when Next.js is generating the new requested path isFallback will be true which means NextJs is generating the page!
  - if a link component is refering to the dynamic page, it'll be automatically generated with scroll (ref: [video 27](https://www.youtube.com/watch?v=j4nAZaPQzwc&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH&index=27&ab_channel=Codevolution) )
  - 
  <img src="https://user-images.githubusercontent.com/52382282/172066214-558a7d93-f1c8-413e-8598-207180ccbea3.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172066408-88b9951a-247f-4bd3-9c1a-86a140e680fa.png" alt="drawing" width="800"/>






