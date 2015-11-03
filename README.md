# twitter-feed
This is a simple lazy loading twitter feed that uses a handle to fetch tweets.

The API fetches tweets from a specified twitter handle. It utilises Angular.js, Node.js and Twitter's API.

The layout uses masonry.js to tile the tweets on the screen.

#Installing and running

Ensure that you have [Node.js](http://nodejs.org/) installed

Clone the git repo
```
git clone https://github.com/joeynimu/twitter-feed.git
```

The config.js file contains the Twitter API keys. I have used my own app keys but i recommend you use your own but you can use as it is for demo purposes.

**Changing Twitter API keys to your own**

*You can skip this step but i recommend not to when using the app in production*

Open config.js file.

Creat your own Twitter app [here](https://apps.twitter.com/)

Generate your app's keys and replace mine with yours in the config.js file.

Install node dependancies:
```
npm install
```

Run and start application

```
npm start
```
Go to [http://localhost:5000](http://localhost:5000)

##Emulating and Testing in Mobile Devices; Android/IOS

The Feed API is made using html5 and javascript and it should work on android and IOS.

To test this, [install ripple emulator on chrome](https://chrome.google.com/webstore/detail/ripple-emulator-beta/geelfhphabnejjhdalkjhgipohgpdnoc?hl=en)

After successfully adding the ripple emulator to Google Chrome, head back to the [app's URL](http://localhost:5000/)

You should see the emulators icon on the rop right corner. Click on it and select the device you would like to emulate.
