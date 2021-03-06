# txtlss hackiesacks API
<img src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/> <img src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/> <a href="https://txtlss-hackiesacks.herokuapp.com/" target="_blank"><img src="https://img.shields.io/badge/heroku%20-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white"/></a>
## Running Locally

Make sure you have [Node.js](http://nodejs.org/) (atleast v12.13.0, npm v6.12.0) installed.

```sh
git clone https://github.com/abhinavchawla13/txtlss-hackiesacks.git
cd txtlss-hackiesacks
npm install
npm run start
```

## Environment Variables

Add a `.env` file in the root folder (you should setup your LiveChat, IBM Watson Credentials):

```
PORT=8081
NODE_ENV=development
LIVECHAT_USERNAME=
LIVECHAT_PASSWORD=
LIVECHAT_WEBHOOK_KEY=
LIVECHAT_WEBHOOK_KEY_START=
LANGUAGE_TRANSLATOR_URL=
SPEECH_TO_TEXT_URL=
TEXT_TO_SPEECH_URL=
TONE_ANALYZER_URL=
LANGUAGE_TRANSLATOR_API=
SPEECH_TO_TEXT_API=
TEXT_TO_SPEECH_API=
TONE_ANALYZER_API=
MONGODB_URI=

```

Add a `ibm-credentials.env` file in the root folder for automatic watson authentication.

## Deployment

Heroku pipeline is set to auto deploy `master` branch currently.


## Some screenshots

<p float="left">
  <img src="https://i.imgur.com/gYYcA3R.png" width="300" />
  <img src="https://i.imgur.com/ADh62gh.png" width="300" /> 
</p>
