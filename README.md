#Webhooks Alpha

Webhooks let your app connects to APIs and listen to different events taking place in them. For example, you can get notified whenever someone creates a new commit on GitHub, sends a message on Slack, or sends you a message on Facebook Messenger.

RapidAPI Webhooks let's you easily connect to different Webhooks. By using RapidAPI, you don't need to create a publicly accessible endpoint for the webhooks to reach, meaning:

- **It's easier to debug on localhost** - you don't need a public IP to debug.
- **It's more secure** - because you have a direct SSL socket to RapidAPI, no one else can send you messages.
- **It's faster** - we keep a socket open between your servers and RapidAPI's, eliminating a lot of protocol overhead.

###Apply for alpha access
If you already have access to this alpha - skip right into Using Webhooks.
If you want to apply for the alpha - fill in the [application form](https://iddogino1.typeform.com/to/Fx4PwV).

###Using Webhooks
If you head over to [RapidAPI](https://rapidapi.com) and login, you can see which packages have webhooks as they'll have a **Webhooks** tag on them.

Currently the following packages are supported:

- [Slack](https://rapidapi.com/package/Slack)
- [FacebookMessenger](https://rapidapi.com/package/FacebookMessenger)
- [PubNub](https://rapidapi.com/package/PubNub)
- [GitHub](https://rapidapi.com/package/Github)

Once you look at the API, on the overview screen, you should see all the webhooks it supports. Clicking on a webhook will take you to it's docs, which will have all the steps needed to connect to it.

On the right panel you'll have a code snippet that you can copy to your app. The function in that code snippet will get called whenever that event happens. (Don't forget to download the SDK for your preferred language!)

You can also use the **Test Event** button in that screen to test the connection in your code. That button will fire up a fake event, so that you can see your app is actually connected properly. Simply copy the code snippet into your application, run it, and press the **Test Event** button. No setup necessary!

Once you've found the event you would like to listen to and tested that it works, follow the steps provided on how to setup the webhook (note: it's important to use the provided URL as a callback), and you're ready to go! Also, it's important that you provide the required parameters for that event. 

###Feedback
As this is an Alpha feature, we're always looking for feedback around your expirience with it. You can submit feedback in 2 ways:

- As issues in this repo - this is the best way to report bugs / suggestions.
- In the Slack group - you should've recieved an invite to the Slack group when you were added to the Alpha.
