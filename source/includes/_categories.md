# Categories

## Get All Categories

```shell
curl 'http://api.incmty.com/api/v1/categories'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "1.0.0",
    "version": "v1"
  },
  "category": [
    {
      "id": 1,
      "name": "Taller"
    },
    {
      "id": 445,
      "name": "Premiación"
    },
    {
      "id": 1234,
      "name": "Conferencia"
    }
  ]
}
```

With this endpoint you should receive all the event categories we have in our Database.

### HTTP Request

`GET http://api.incmty.com/api/v1/categories`

### Query Parameters

Parameter | Description
--------- | -----------
NONE | This endpoint needs no parameters.

