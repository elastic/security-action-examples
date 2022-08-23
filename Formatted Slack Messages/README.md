This action generates a nicely formatted slack message, with links back to the alert in question. The example was built based of a malware alert. Please adapt the used fields according to the detection you are using this on.

This assumes you have a slack [webhook](https://api.slack.com/messaging/webhooks) already defined for the workspace and channel in question.

The webhook URL should look similar to:

`https://hooks.slack.com/services/xxxxxx/xxxxxxx/xxxxxxxx`

**Example Result:**
![Result](Slack%20Example%20Result.png)

**Example Connector Config:**
![Result](Connector%20Config%20Example.png)
