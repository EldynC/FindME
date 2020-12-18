# Welcome to StackEdit!

## Overview
This is a work-in-progress community policing app focused on the simplicity of letting users report suspicious events, vehicles or people in their area. 


## Tech Stack - Back end
For the back end I decided to use a model called PERN which consists of PostgresQL, Express, React(Native) and Node. I created my own REST API that calls from the markers table from my database(hosted on ElephantSQL) as well as the users table. Every user that gets created gets their password encrypted using bcrypt. For authentication I decided to use JWT, and those tokens are stored in the AsyncStorage on the front-end. To connect the front-end to the server for real-time updates I am using socket.io.

## Tech Stack - Front end
The front end of the app is developed React Native and Expo, which I used to demo the app on my iPhone 11 and debug. Some of the libraries I used include: 
- React Native Maps: Used for generating the map and rendering markers
- Socket.io: Used for connecting the front end and back end in real time
- React Native Gesture Handler: Used for Text input
- React Native Async Storage: Used for storing JWT Authorization tokens
- React Native SVG: Used for rendering the Logo
- React Navigation: Used for navigating the screens in the app
- Expo Linear Gradient : Used for generating nice background gradients

## Tech Stack - Back end
The back end of the app is developed using Express(along with cors), bcrypt, jwt, socket.io and Node.
- bcrypt: Used for hashing user passwords.
- Express: Used for creating the API.
- jwt: Used for creating authentication tokens. 
- socket.io: Used for making real time connections between front end and back end.
- Node: Used for running the code on the back end.

## To-do

- [ ] Have users be able to add friends.
- [ ] Have user be able to upload their own profile picture.
- [ ] Finish sign out and token refresh in navigation dispatch.
- [ ] Make marker rendering more efficient.
- [ ] Make markers expire after a certain period of time.
- [ ] Make sockets more efficient by closing connections.
- [ ] Make the UI look 🌟*Nicer*🌟

## Demo - Log in and Report
<img src="https://imgur.com/WUbKbM7.gif" width=200><br>
...More demos to come
## Credits

I will fill this out as I go but I primarily want to thank Conner Le for helping me design the preliminary UI when we contested in the DFW Adobe XD Jam.


