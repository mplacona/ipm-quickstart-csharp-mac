# IP Messaging Quickstart for C# on a Mac (ASP.NET MVC)

This application should give you a ready-made starting point for writing your
own messaging apps with Twilio IP Messaging. Before we begin, we need to collect
all the config values we need to run the application:

| Config Value  | Description |
| :-------------  |:------------- |
Service Instance SID | Like a database for your IP Messaging data - [generate one in the console here](https://www.twilio.com/user/account/ip-messaging/services)
Account SID | Your primary Twilio account identifier - find this [in the console here](https://www.twilio.com/user/account/ip-messaging/getting-started).
API Key | Used to authenticate - [generate one here](https://www.twilio.com/user/account/ip-messaging/dev-tools/api-keys).
API Secret | Used to authenticate - [just like the above, you'll get one here](https://www.twilio.com/user/account/ip-messaging/dev-tools/api-keys).

Read more about adding environment variables on a Mac [here](http://osxdaily.com/2015/07/28/set-enviornment-variables-mac-os-x/).

## A Note on API Keys

When you generate an API key pair at the URLs above, your API Secret will only
be shown once - make sure to save this in a secure location, 
or possibly your system environment variables.

## Setting Up The Application

After downloading the repo make sure you have all the environment variables properly set.

You should now be ready to rock! On your terminal run `dnx web` and point your browser to http://localhost:5000, 
and you should land on the home page of our basic chat application. Open it up in a few browser
tabs and start chatting with yourself!

Due to the dependencies used, the application will only run on DNX 451 and not on DNXCORE 5

![screenshot of chat app](https://s3.amazonaws.com/howtodocs/quickstart/ipm-browser-quickstart.png)

## License

MIT
