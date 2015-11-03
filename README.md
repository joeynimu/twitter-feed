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

Open config.js file.
Creat your own Twitter app [here](https://apps.twitter.com/)
Generate your app's keys and replace mine with yours in the config.js file.

Install node dependancies:
```
npm install
```
