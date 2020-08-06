# sugarcrm-rest-client

HTTP REST client for calling SugarCRM APIs

### Using REST Client

[sugarcrm.http](sugarcrm.http) can be used with REST client (IntelliJ/VSCode) - you can run REST requests directly from the IDE.

Rest client uses dynamic variable substitution by providing a settings json file. For IntelliJ, create a http-client.private.env.json with the following values

```{
  "local": {
    "rest_url": "http://localhost/rest/v10",
    "username": "sugar",
    "password": "sugar"
  }
 }
```

Settings JSON for Rest Clients (IntelliJ / VSCode)

For VSCode, install REST Client plugin, then open your settings as JSON and enter the JSON from above in rest-client.environmentVariables

SugarCRM provides multiple API versions (starting from v10) - all the REST APIs provided in this article are from v10, but you can always use the latest API version as part of your SugarCRM version.

For detailed explanation, visit [the CheatSheet at SevenTunes.com](https://seventunes.com/sugarcrm-api-cheatsheet/)
