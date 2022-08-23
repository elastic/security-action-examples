For cloudflare firewalls, this assumes you have a defined zone which you would like to block traffic from a source IP address which was the subject of a detection rule.

The webhook URL should look similar to:

`https://api.cloudflare.com/client/v4/zones/xxxxxxxxxxxx/firewall/rules`

**Example Result:**
![Result](Cloudflare%20Example%20Result.png)

**Example Connector Config:**
![Result](Connector%20Config%20Example.png)
