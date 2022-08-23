<h1><img src="https://static-www.elastic.co/v3/assets/bltefdd0b53724fa2ce/blte046ae7d78156afb/601081790839e910126d7653/security-logo-color-32px.svg"/>  Security Action Examples</h1>

This repository contains a few examples of [actions](https://www.elastic.co/guide/en/security/current/rules-ui-create.html#rule-notifications) that can be added to rules within Elastic Security. Each subdirectory contains the following files:

- A JSON file containing the action content. Please feel free to change the variables and other content as you see fit.
- A README file with specific instructions for the action connector in question.
- A screenshot of the connector configuation in Kibana's [connector management](https://www.elastic.co/guide/en/kibana/current/action-types.html) page.
- A screenshot of the expected outcome when an action runs successfully.

_**Please use these actions with caution, and test appropriately. Do not blindly add an action to a detection rule if you are unsure of what the outcome is, or how it will impact your organization. You should follow any operational procedures you may have in place for any form of automation scenarios.**_ 

The screenshot below shows an example of what one of these actions would look like as part of a detection rule configuration:

![Result](Action%20Setup%20Example.png)

# License

Copyright Elasticsearch B.V. and/or licensed to Elasticsearch B.V. under one or more contributor license agreements. Licensed under the Elastic License 2.0; you may not use these artifacts except in compliance with the Elastic License 2.0

Contributors must sign a [Contributor License Agreement](https://www.elastic.co/contributor-agreement) before contributing code to any Elastic repositories.
