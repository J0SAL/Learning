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
  
  - ### Static Generation
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
  
  - Issues
  - 
  <img src="https://user-images.githubusercontent.com/52382282/172118418-cb7323f6-65b8-4f0b-a147-2459863a321a.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172120503-ecbd7b94-970d-4f6c-a646-9b708891d408.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172120539-18143bc5-55e1-418b-89f2-2d672efe6ba6.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172120588-7c0983b4-0d76-460a-9e3f-9199c99cd06e.png" alt="drawing" width="800"/>
   
  - Fixes 
  - 
  <img src="https://user-images.githubusercontent.com/52382282/172122505-08cafb4f-b28b-41af-81da-c88f822b4700.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172122566-5b70ab4e-0cc8-4855-9701-a9c7976ff93f.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172122837-b358ba25-dab7-4150-8cb3-548021d7cc76.png" alt="drawing" width="800"/>
  
  - ### Server Side Rendering
  -
  <img src="https://user-images.githubusercontent.com/52382282/172346960-3b3c8aec-aef1-49f4-8675-28f407f6143e.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172348952-0544fff3-cc37-4bc0-8b0a-c84d03168fca.png" alt="drawing" width="800"/>
  <img src="https://user-images.githubusercontent.com/52382282/172349010-710f91d9-8dda-4c8e-ae6c-a585c99df083.png" alt="drawing" width="800"/>
 
 - ### Client Side Data Fetching
   <img src="https://user-images.githubusercontent.com/52382282/172372491-7c96b08e-b7a2-4e9d-9c5e-d487ab2484d1.png" alt="drawing" width="800"/>
   
   - #### SWR (Hook) for Client-side Data Fetching is preferred and is easy
   - #### YT-38 - [Pre rendering + Client side Data Fetching + Shallow Routing](https://www.youtube.com/watch?v=yFvLLPBubfw&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH&index=38&ab_channel=Codevolution)
   <img src="https://user-images.githubusercontent.com/52382282/172375752-88834799-9506-4488-8196-768adf674580.png" alt="drawing" width="800"/>
   <img src="https://user-images.githubusercontent.com/52382282/172375950-10d8ac54-f372-402d-95c4-217beb8792f5.png" alt="drawing" width="800"/>










