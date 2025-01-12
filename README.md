# Music API Web Application
Welcome to the Music API! You can access any song and listen to it. Below are some useful links and information.

## Features
- Search for a song to listen.
- Displays detailed information about the song.
- Click ▶ to listen to the song.

## Technologies Used
- Node JS
- Spotify API
- HTML
- CSS
- JavaScript

## Pre-Requisites
Before getting started, there are some pre-requisites to keep in mind:
- This music app requires Spotify Premium, so you'll need a premium account to use it.
- [Set up account](#set-up-account) using your Spotify Credentials.


> **Note:** You'll require a premium account only for listening to the song. You will still be able to fetch the song details without having a premium account.

## Installation
Follow these steps to install the project.
1. Clone the repository to your local machine.
2. Run command `npm i` to install all the dependencies.
3. Run command `npm start` to start the server
4. Visit [http://localhost:3000](http://localhost:3000)

## API Integration
This web application uses Spotify API to fetch the song data.

## Set Up Account
Set up your developer account to get access to `CLIENT_ID` and `CLIENT_SECRET` required to use Spotify API
1. Visit the site: [Spotify for Developers](https://developer.spotify.com/).
2. Log into the [Dashboard](https://developer.spotify.com/dashboard) using your Spotify account.
3. Click [Create app](https://developer.spotify.com/documentation/web-api/concepts/apps)
    - Add `http://localhost:3000/callback` to "Redirect URIs".
    - Select `Web API` for the question asking which APIs are you planning to use.
    - Similarly add other details.
4. Once you have created your app, you will have access to the app credentials. These will be required for API authorization to obtain an access token.
5. Use the access token in your API requests. 

## Set up .env file
1. Set `CLIENT_ID` = 'Your-Client-Id'
2. Set `CLIENT_SECRET` = 'Your-Client-Secret'
3. Set `REDIRECT_URI` = 'http://localhost:3000/callback'

> **Note:** Open your [Spotify on Web](https://open.spotify.com/) side by side with the app to listen to the song. If you still encounter `NO_ACTIVE_DEVICE` error, switch to spotify tab and simply click play and then pause ( to any song that had been played previously), this will ensure that Spotify is running correctly in background and then switch back to the Music API and refresh the webpage.

## Demo 

**Login Page**
![Screenshot (383)](https://github.com/user-attachments/assets/09ba3932-c45f-406a-8d7b-90a9272b1323)

**Spotify Login Page**
![Screenshot (382)](https://github.com/user-attachments/assets/8861ac96-3805-4117-a3fe-ba63064eb7f8)

**Search Page**
![Screenshot (384)](https://github.com/user-attachments/assets/49c75839-1abf-4602-8329-f0d36caff9a4)

**Playback Started**
![Screenshot (385)](https://github.com/user-attachments/assets/e2561f70-6982-47fd-bda0-ad2392504fa1)


## ENJOY!!😃

## Legal
By using Spotify Web API, you accept the [Spotify Developer Terms of Service](https://developer.spotify.com/terms).




