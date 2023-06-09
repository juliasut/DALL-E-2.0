## [Live Demo](https://dall-e-2-0-silk.vercel.app/)


<img width="1232" alt="dall-e-2-0" src="https://user-images.githubusercontent.com/81769855/227663086-a1cc7853-8eaf-4c2b-a2bc-de731ab77a8e.png">


## Learning Objective:

- Learn how to handle storing images in database
- Learn using new third party API (openAI)
- Learn new CSS framework

## Built using:

1. Node.js, Express.js, MongoDB, and React.js together form the powerful MERN stack
2. Tailwind: The most popular CSS framework nowadays
3. OpenAI's DALL-E model: A deep learning model that generates images from text input
4. Cloudinary: A cloud-based image storage service


## Part I - FE Routing

- [x] - Create and import Components to route to
- [x] - Wrap app in BrowserRouter
- [x] - Add Links to routes in navbar and Routes to components in main

## Part II - BE Routing

- [x] - Create simple instance of BE API: 
  - [x] - Start server
  - [x] - Connect MongoDB
  - [x] - Create post model to save them in database
  - [x] - Add post routes for creating and retrieving the posts
  - [x] - Add dalle routes to generate the data from the openai API 

## Part III - BE Storing A Post with an Image
- [x] - Add Cloudinary to store images and give image url
- [x] - Only store image urls in Post models in mongodb

## Deploy 

BE is deployed on [Render](https://render.com/)

FE is deployed on [Vercel](https://vercel.com/)

Check it out [HERE](https://dall-e-2-0-silk.vercel.app/)
