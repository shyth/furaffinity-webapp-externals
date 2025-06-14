# furaffinity-webapp-externals
I made this repo to *hopefully* get a webapp version of the furaffinity website working.

## How to install it:
There are two ways to install it. The new method is a little tricky, but it takes you directly to FurAffinity when you open the app. The old method is easier, but instead of going directly to the website, opening the app takes you to a different website, which redirects you to FurAffinity.

### New Method:
Save this link `javascript:(function () {    var link = document.createElement('link');    link.rel = 'manifest';    link.href = 'https://raw.githubusercontent.com/shyth/furaffinity-webapp-externals/refs/heads/main/manifest.json';    document.head.append(link);    link.onload = function () {        window.navigator.vibrate([100, 50, 400]);    };})();` to your Bookmarks Bar. 
Then go to [FurAffinity](https://furaffinity.net/) and open the bookmarked link while the site is loading.

### Old Method:
If you're having trouble getting the timing down, you can install the old redirect here:
https://shythevans.w3spaces.com/
