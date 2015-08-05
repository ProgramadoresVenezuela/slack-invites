# slack-invites
A landing page to invite users to your Slack organization. You can point users to this page to fill in their emails and receive an invite (`http://APPID.stamplayapp.com`)

![Screenshot](./images/screenshot.png)

## How it works

This landing page is built using the following blocks:

* [Webhook](https://stamplay.com/docs/rest-api#user)
* [Slack]



-----------------------
# Developing

First, clone this repository :

    git clone git@github.com:Stamplay/slack-invites
    
Or download it as a zip file
	
	https://github.com/Stamplay/slack-invites/archive/master.zip 

After launching `bower install` you need to upload the frontend files in your app by using the [CLI tool](https://github.com/Stamplay/stamplay-cli):

```js
cd your/path/to/slack-invites
stamplay init
/*
 * You'll be prompted to type the appId and API key of your Stamplay app
 */
stamplay deploy
```

-----------------------
