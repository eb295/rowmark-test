# Google Authentication Web App

A simple web application that demonstrates Google Sign-In authentication using the Google Identity Services JavaScript library.

## Features

- Google Sign-In authentication
- JWT token decoding
- User information display
- Sign-out functionality

## Setup

1. Clone this repository
2. Ensure you have a valid Google Cloud Platform project with the Google Identity Services API enabled
3. Replace the `data-client_id` in `index.html` with your own Google client ID
4. Serve the application using a local web server (e.g., `python -m http.server 8000`)
5. Open your browser and navigate to `http://localhost:8000`

## How It Works

This application uses the Google Identity Services JavaScript library to authenticate users. When a user signs in with their Google account, the application decodes the JWT token and displays the user's name on the welcome screen.

## Project Structure

- `index.html`: Main HTML file with the Google Sign-In button configuration
- `style.css`: Stylesheet for the application
- `script.js`: JavaScript file that handles authentication logic and UI updates

## Configuration

To use your own Google client ID, update the following line in `index.html`:

```html
data-client_id="YOUR_CLIENT_ID_HERE"
```

You can obtain a client ID from the [Google Cloud Console](https://console.cloud.google.com/) by creating a new project and enabling the Google Identity Services API.