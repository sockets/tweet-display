# Tweet Stream Display
Tracks and displays recent filtered tweets to a webpage which can easily be displayed into an OBS stream.

## Screenshots

![Preview](https://i.imgur.com/YRQHk3m.jpeg)

## Installment

To use this project:
- Create a project in the twitter developer portal to get the BEARER_TOKEN
- Install dependencies with `npm i`
- Create and edit .env file using the example provided below
- Run the app with `npm start`
- Visit `localhost:3000` (or .env port)

### Example .env
```
BEARER_TOKEN=AAAAAAAAGETTHISSFROMTWITTER
PORT=3000
TWITTER_USER=socketxo
TWITTER_HASHTAG=socket
```

Links
-----

- [Twitter Developer Portal](https://developer.twitter.com/en/portal)
