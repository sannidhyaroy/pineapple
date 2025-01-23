# Pineapple
This app is no longer being developed due to new Reddit API pricing. If you would like to use it, please create your own API key and build the app using instructions below 👇


Reddit client for Android highlighting Material Design 3 aspects, with dynamic color and a clean, more minimalistic design. (WIP)

<img src="PineapplePreview.png">

# Build notes
Before building, you must do the following steps so that OAuth and basic network functionality will work:
1. Sign-in, and create a new app on https://www.reddit.com/prefs/apps.
2. Choose `installed app` as type and set the redirect URI to `pineapple://login`, then proceed. It will generate a client secret.
3. Build in Android Studio or using gradle on the command line and install it.
3. Paste the client secret in the app's setup screen.