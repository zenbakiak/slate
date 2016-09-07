# Themes

```shell
curl 'http://api.incmty.com/api/v1/themes'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "1.0.0",
    "version": "v1"
  },
  "theme": [
    {
      "id": 1,
      "name": "Emprendimiento social"
    },
    {
      "id": 8,
      "name": "Energía"
    },
    {
      "id": 7,
      "name": "Entretenimiento"
    },
    {
      "id": 11,
      "name": "Impulso al emprendimiento"
    },
    {
      "id": 2,
      "name": "Inversión"
    },
    {
      "id": 14,
      "name": "Marketing"
    },
    {
      "id": 3,
      "name": "Mujeres emprendedoras"
    },
    {
      "id": 6,
      "name": "Salud"
    },
    {
      "id": 4,
      "name": "Tecnologías emergentes"
    }
  ]
}
```

With this endpoint you should receive all the Topics (Themes) we have in our Database.


### HTTP Request

`GET http://api.incmty.com/api/v1/themes`

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | String | Name of the topic (theme)
