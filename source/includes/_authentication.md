# Authentication

> To authorize, use this code:


```shell
# With shell, you can just pass the correct header with each request
curl 'http://api.incmty.com/api/v1/«ENDPOINT_NAME»'
  -H 'Authorization: Token token="«your API key»"'


# Make sure to replace `«your API key»` with your API key.
```

IncMty uses API keys to allow access to the API.

IncMty expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: Token token="something something"`

> JSON response structure:

```json
{
  "header": {
    "feed_version": "1.0.0",
    "version": "v1"
  },
  "entity": []
}
```

<aside class="notice">
You must replace <code>something something</code> with your organizational API key.
</aside>

If your API key is valid: You should receive a JSON with the following structure