# TravelVenture

Full-stack Web Application

## Link of the Website
https://devansh-travelventure.onrender.com/

## Screenshots of the Website
![](https://github.com/user-attachments/assets/67b8ea27-0ab9-4934-9b48-b4f93a302459)

![](https://github.com/user-attachments/assets/3d6ebf62-1867-4b8b-9c07-736c10a96460)

![](https://github.com/user-attachments/assets/8f279748-0225-461e-b296-c7faf7b4e4ad)

![](https://github.com/user-attachments/assets/aaa0c8d5-26c4-41b9-8455-69f488ad19c9)

![](https://github.com/user-attachments/assets/7c9d3f7b-7abd-4728-b345-265d8571a747)

![](https://github.com/user-attachments/assets/7456b9f6-7254-4d5d-83c1-1761696df415)

![](https://github.com/user-attachments/assets/cddfea04-edf7-43f8-ab17-a58c3e1d49fc)

## Technologies Used

- [Express.js](https://github.com/expressjs/express) minimal, unopinionated backend framework to keep serverside boilerplate as low as possible. Especially useful for learning how to piece different technologies together to develop a complete backend.
- [Express-Session](https://github.com/expressjs/session) to learn how cookies work to deliver a rich user experience through client and serverside cookies.
- [Passport.js](https://github.com/jaredhanson/passport) for authentication and authorization.
- [MongoDB](https://github.com/mongodb/mongo) as the primary NoSQL database to store Destinations, users, reviews and session details.
- [Mongoose](https://github.com/Automattic/mongoose) as an ORM(Object relation mapping) library to interact with MongoDB.
- [Cloudinary](https://github.com/cloudinary/cloudinary_npm) to store images of Destinations when users create new Destinations, and to optimize them for when client-side requests them.
- [Mapbox](https://github.com/mapbox/mapbox-gl-js) to deliver an interactive map for users to visually see the location of Destinations through a cluster map and a zoomed in map for each Destination.
- [EJS (Embedded JavaScript Templates)](https://github.com/mde/ejs) as a templating language to create dynamic user experices.
- [Bootstrap](https://github.com/twbs/bootstrap) as the driving CSS framework to create visually appealing user experiences.
- Render to host the complete application

## Working of the Website

## Website Overview

This website allows users to authenticate, add Destinations, post reviews and comments, edit and delete submissions, and display the location of each Destination on a map. The website is powered by a MongoDB infrastructure that stores data for reviews, comments, and other relevant information.

## Features

1. User Authentication
   Registration: Users can sign up by creating a new account.
   Login: Registered users can log in with their credentials.
   Logout: Users can log out from their account.
   Session Management: Users remain logged in across different sessions until they explicitly log out.
2. Destination Management
   Add New Destination: Logged-in users can add new Destinations by providing details such as the name, location, price, and description.
   View Destinations: All users can view a list of available Destinations, including details and images.
   Edit Destination: Users can edit the Destinations they’ve added. This includes updating details like name, location, and description.
   Delete Destination: Users can delete Destinations they have added if they no longer want them to be listed.
3. Reviews and Comments
   Add Reviews/Comments: Users can post reviews and comments on individual Destinations, sharing their experiences or opinions.
   Edit Reviews/Comments: Users can edit their own reviews and comments if they want to change their content.
   Delete Reviews/Comments: Users can delete their own reviews and comments.
4. Map Integration
   Display Destination Locations: Each Destination’s location is displayed on an interactive map, allowing users to see where the Destination is located geographically.
   Map Interaction: Users can interact with the map to zoom in/out and view the precise location of each Destination.

## To run this project on your system:

Create an .env file and add values to the following variables:

```
CLOUDINARY_CLOUD_NAME=<Your Cloudinary cloud name>
CLOUDINARY_KEY=<Your Cloudinary key>
CLOUDINARY_SECRET=<Your Cloudinary secret>
MAPBOX_TOKEN=<Your Mapbox token>
DB_URL=<Your MongoDB atlas URL or local MongoDB URL>
```
