# Swiftify App
Interactive Spotify-themed web application using React, NodeJS and MySQL RDS database

Application can be run as follows:

- cd to `spotifyApp/client`
- `npm install`
- `npm run start`
- In another terminal, cd to `spotifyApp/server`
- `npm install`
- `npm run start`

## File structure

`client` folder contains the files for the frontend. This was developed using React.

`server` folder contains the files for the backend routes and methods. This was developed in NodeJS.

`data` folder contains the data that was used for the project. The data was obtained from Spotify, specifically a selection of Taylor Swift's albums and songs. The data was hosted on an AWS RDS instance. The database connection information can be found and modified in the `spotifyApp/server/config.json` file.

## Pages
