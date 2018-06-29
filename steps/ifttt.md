# IFTTT - IF THIS THEN THAT

> [IFTTT](https://ifttt.com/discover)

Go to [webhooks settings page at IFTTT](https://ifttt.com/services/maker_webhooks/settings) to copy the URL that has your key:

```
URL: https://maker.ifttt.com/use/<key>
```

Paste it in the `http request node` in Node-RED editor and make sure the `Method` in there is selected: `POST`.

<hr>

### Slack

> Important

Create a [Slack account](https://slack.com): `YOUR_SLACK_NAME.slack.com` or make sure you're the admin or have the credentials of an existing one. Next create a channel name it as per your project's theme (in this pattern, it's called `commands`).

<hr>

* Now go to the following [link](https://ifttt.com/my_applets) to create your applets or click on `My Applets` tab.

![](../img/new-applet.png)

* Click on <img src="../img/plus.png" width="45" height="50"> icon and search for `Webhooks` and click on it.

![](../img/webhook-search.png)

![](../img/webhook.png)

![](../img/webhook-clicked.png)

* Enter event name. Follow the steps like in the following images:

![](../img/turnon1.png)

![](../img/turnon2.png)

![](../img/turnon3.png)

* Now click on the next <img src="../img/plus.png" width="45" height="50"> icon and search for `Slack` (you can always choose any other applet that you want). Accept the associated credentials of the Slack.

![](../img/then-plus.png)

![](../img/slack.png)

<hr>

#### Apply the same way for the rest of the events. The events in this tutorial are:

* `brew`
* `stop_brewing`


![](../img/ifttt-myapplets.png)

<hr>

![](../img/slack-coffee.png)
