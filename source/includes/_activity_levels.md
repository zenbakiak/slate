# Activity Levels (Etapa)

```shell
curl 'http://api.incmty.com/api/v1/activity_levels'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "2.0.6",
    "version": "v1"
  },
  "activity_levels": [
    {
      "id": 2,
      "name": "Idea/Prototipo"
    },
    {
      "id": 4,
      "name": "Startup"
    },
    {
      "id": 5,
      "name": "Scaleup"
    },
    {
      "id": 6,
      "name": "Corporativo"
    },
    {
      "id": 7,
      "name": "Todas las fases"
    },
    {
      "id": 8,
      "name": "Ni Idea (antes de emprender)"
    }
  ]
}
```

With this endpoint you should receive all the activity levels we have, you'll be able to associate with activity_level_id attribute in the schedules endpoint

### HTTP Request

`GET http://api.incmty.com/api/v1/activity_levels`

### Query Parameters

Parameter | Description
--------- | -----------
NONE | This endpoint needs no parameters.


### Params Returned

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | string | Activity level name