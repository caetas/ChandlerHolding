# ChandlerHolding
Automatic generator of Chandler holding your fav album

## Use the Spotify API:
1. Log in into your account or create a new one [here](https://developer.spotify.com/dashboard/).
2. Once in your dashboard, click the green “Create a Client ID” button to fill out the form to create an app or hardware integration.
3. On your developer dashboard page, click on the new app you just created, and on the app’s dashboard page you will find your Client ID just under the header name of your app. Click “Show Client Secret” to access your secondary Client ID.
4. Copy both the ID and the Secret to a *cred.py* file using the following structure:

```python
SPOTIPY_CLIENT_ID = 'your-id'
SPOTIPY_CLIENT_SECRET = 'your-secret'
```

