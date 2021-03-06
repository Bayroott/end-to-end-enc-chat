# End-to-End Encrypted Chat

[![Demo on Heroku](./images/demo.svg)](https://end-to-end-enc-chat.herokuapp.com/) [![Maintainability](https://api.codeclimate.com/v1/badges/d7aa5b3876f126159e26/maintainability)](https://codeclimate.com/github/pskrunner14/end-to-end-enc-chat/maintainability) [![Hackage-Deps](https://img.shields.io/hackage-deps/v/lens.svg)](https://github.com/pskrunner14/end-to-end-enc-chat/network/dependencies)

This is a node chat application with end-to-end encryption. It uses [AES-256](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) and [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) encryption algorithms under the hood. You can either see the *demo* of the app using the button above or alternatively, you can *deploy* your own copy of the app using this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Getting Started

You'll need to install all the npm packages in order to start the app server:

```bash
cd end-to-end-enc-chat/
npm install
```

For running the app while in development:

```bash
npm run dev
```

For simply running the app in production mode:

```bash
npm start
```

**note**: Since this is a demo application I've added the `.env` file containing the environment vars on the root level, however you might not want to do that in production.