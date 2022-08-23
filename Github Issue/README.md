This action creates an issue in a dedicated Github repository, assigns a user, and adds a tag for identification.

This assumes the repository already exists, and the assignee has appropriate permissions. You will also need to generate an API [token.](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

The webhook URL should look similar to:

`https://api.github.com/repos/<org>/<repo>/issues`

**Example Result:**
![Result](Github%20Example%20Result.png)

**Example Connector Config:**
![Result](Connector%20Config%20Example.png)
