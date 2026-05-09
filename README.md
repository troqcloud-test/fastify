# README

This is the [Fastify](https://www.fastify.io/) [Hello world](https://www.fastify.io/docs/latest/Guides/Getting-Started/) example on [TroqCloud](https://troqcloud.com).

The app in this repo is deployed at [https://fastify.troqcloud.app](https://fastify.troqcloud.app).

> Note: Fastify's `.listen` method default binding uses `localhost` (`127.0.0.1`), whereas TroqCloud requires `0.0.0.0`.

## Deployment

See https://troqcloud.com/docs or follow the steps below:

Create a new web service with the following values:
  * Build Command: `npm install`
  * Start Command: `node app.js`

Or simply click:

[![Deploy to TroqCloud](https://troqcloud.com/images/deploy-to-troqcloud-button.svg)](https://troqcloud.com/deploy

That's it! Your web service will be live on your TroqCloud URL as soon as the build finishes.