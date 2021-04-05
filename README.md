# How to connect to Spotify’s API


## 
    Set Up Your Account

To use the Web API, start by creating a Spotify user account (Premium or Free). To do that, simply sign up at [www.spotify.com](http://www.spotify.com/).

When you have a user account, go to the [Dashboard](https://developer.spotify.com/dashboard) page at the Spotify Developer website and, if necessary, log in. Accept the latest [Developer Terms of Service](https://developer.spotify.com/terms) to complete your account set up.


## 
    Register Your Application

Any application can request data from Spotify Web API endpoints and many endpoints are open and will return data without requiring registration. However, if your application seeks access to a user’s personal data (profile, playlists, etc.) it must be registered.

You can [register your application](https://developer.spotify.com/documentation/general/guides/app-settings/#register-your-app), even before you have created it.

Go to the [Dashboard](https://developer.spotify.com/dashboard) page at the Spotify Developer website, and click on ‘My New App.”

There you set the app name and description.

We have different authorization flows to connect with Spotify’s API, in this case we are using .

[Client Credentials Flow](https://developer.spotify.com/documentation/general/guides/authorization-guide/#client-credentials-flow).


## 	Run the application

Clone or download [the repository](https://github.com/amanganello/spotifyExample). As we are using ES6 syntax the scripts should be added to the index.html using typ=”module”, this means that running directly the index.html file on the browser will throw an error. You need to run it using a web server, I used [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) as it is added as extension, feel free to use any other you want.

There are more simple examples that demonstrate the capabilities of the Spotify Web API on: [https://developer.spotify.com/documentation/web-api/libraries/](https://developer.spotify.com/documentation/web-api/libraries/)
