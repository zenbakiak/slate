# Activity Trends (Recursos del emprendedor)

```shell
curl 'http://api.incmty.com/api/v1/activity_trends'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "2.0.6",
    "version": "v1"
  },
  "activity_trends": [
    {
      "id": 3,
      "name": "Capital",
      "activities_count": 2
    },
    {
      "id": 5,
      "name": "Mentores",
      "activities_count": 0
    },
    {
      "id": 7,
      "name": "Socios",
      "activities_count": 1
    },
    {
      "id": 8,
      "name": "Ideas",
      "activities_count": 2
    },
    {
      "id": 9,
      "name": "Tecnologías",
      "activities_count": 3
    }
  ]
}
```

With this endpoint you should receive all the activity trends we have, you'll be able to associate with activity_trend_id_refs param in the schedules endpoint

### HTTP Request

`GET http://api.incmty.com/api/v1/activity_trends`

### Query Parameters

Parameter | Description
--------- | -----------
NONE | This endpoint needs no parameters.


### Params Returned

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | string | Activity trend name
activities_count | Integer | Activities related with this activity_trend