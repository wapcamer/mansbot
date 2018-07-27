
<script src="https://cdn.jsdelivr.net/npm/botfuel-webchat-client@3.13.8"></script>
  <script>
    BotfuelWebChat.init({
      appToken: '1409617777135',
      size: { width: 500, height: 600 },
      startOpen: true,
      startFullScreen: false
    });


# botfuel-sample-starter

This sample bot is used in [**Getting Started**](https://docs.botfuel.io/dialog/tutorials/getting-started).

## Create an app

* Create a new app on Botfuel Trainer (https://app.botfuel.io).

* Add an intent with lable `name` with the following training phrases for examples:

  * My name is Bob.

* Add an intent with lable `greetings` with the following training phrases for examples:
  * Hi
  * Hello

## How to run the bot

Clone the repository:

```shell
git clone git@github.com:Botfuel/botfuel-sample-starter.git
```

Install dependencies:

```shell
cd botfuel-sample-starter
npm install
```

Start the bot:

```shell
BOTFUEL_APP_TOKEN=<YOUR_BOT_ID> BOTFUEL_APP_ID=<YOUR_BOTFUEL_APP_ID> BOTFUEL_APP_KEY=<YOUR_BOTFUEL_APP_KEY> npm start
```

If you set your app credentials right, you should see:

```shell
2017-12-07T16:12:09.131Z - info: [Config] You didn't specify any config file, using default config.
2017-12-07T16:12:09.131Z - info: [Environment] BOTFUEL_APP_TOKEN=<YOUR_BOT_ID>
2017-12-07T16:12:09.133Z - info: [Environment] BOTFUEL_APP_ID=<YOUR_BOTFUEL_APP_ID>
2017-12-07T16:12:09.133Z - info: [Environment] BOTFUEL_APP_KEY=<YOUR_BOTFUEL_APP_KEY>
```

Try typing `Hello` or `My name is <YOUR_NAME>`!

## Need help ?

* See [**Getting Started**](https://docs.botfuel.io/platform/tutorials/getting-started) to learn how to run a bot in minutes.
* See [**Concepts**](https://docs.botfuel.io/platform/concepts) for explanations about the internals of the SDK.

## License

See the [**License**](LICENSE.md) file.
