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

- ## Imp Points
- ### Features
  1. Routing
  2. Pre-rendering
      - #### Static Generation
        - mention possible values of pages that are to be dynamically generated using getStaticPaths()
        - getStaticPaths fallback : [false , true, 'blocking'] 
        - when Next.js is generating the new requested path isFallback will be true which means NextJs is generating the page!
        - if a link component is refering to the dynamic page, it'll be automatically generated with scroll (ref: [video 27](https://www.youtube.com/watch?v=j4nAZaPQzwc&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH&index=27&ab_channel=Codevolution))
      - #### Server Side Rendering
      - #### Client Side Data Fetching
        - SWR (Hook) for Client-side Data Fetching is preferred and is easy
        - YT-38 - [Pre rendering + Client side Data Fetching + Shallow Routing](https://www.youtube.com/watch?v=yFvLLPBubfw&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH&index=38&ab_channel=Codevolution)










