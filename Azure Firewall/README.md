For Azure firewalls, this assumes you have a defined firewall policy, with a temporary rule collection group dedicated to this use case- blocking traffic to a destination ip address which was the subject of a detection rule. Whenever this action is invoked, the content in the temporary collection group is overwritten. It is also assumed that when this runs, the temporarily created rule with be assessed and assigned to a permanent rule collection group.

The webhook URL should look similar to:

`https://management.azure.com/subscriptions/<subid>/resourceGroups/<resource group name>/providers/Microsoft.Network/firewallPolicies/<firewall-policy-name>/ruleCollectionGroups/<rule-collection-group-name>?api-version=2022-01-01`

You will need to create a service account and generate an authentication [token](https://mauridb.medium.com/calling-azure-rest-api-via-curl-eb10a06127) for it.

**Example Result:**
![Result](Azure%20Example%20Result.png)

**Example Connector Config:**
![Result](Connector%20Config%20Example.png)
