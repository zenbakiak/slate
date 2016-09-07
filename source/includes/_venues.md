# Venues

```shell
curl 'http://api.incmty.com/api/v1/venues'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "1.0.0",
    "version": "v1"
  },
  "venue": [
    {
      "id": 1,
      "name": "Campus Monterrey - Anexo CETEC 1erPiso",
      "description": "Anexo CETEC 1erPiso",
      "capacity": 400,
      "latitude": "25.649731",
      "longitude": "-100.285666"
    },
    {
      "id": 2,
      "name": "Campus Monterrey - Aulas 1, salón 104",
      "description": "Aulas 1, salón 104",
      "capacity": 200,
      "latitude": null,
      "longitude": null
    },
    {
      "id": 3,
      "name": "Campus Monterrey - Aulas 1, salón 113",
      "description": "Primer piso",
      "capacity": 100,
      "latitude": "25.651913",
      "longitude": "-100.290259"
    },
    {
      "id": 200,
      "name": "Campus Monterrey - Aulas 1, salón 114",
      "description": "Primer piso",
      "capacity": 120,
      "latitude": "25.651913",
      "longitude": "-100.290259"
    },
    {
      "id": 12,
      "name": "Campus Monterrey - Aulas 1, salón 115",
      "description": "Primer piso",
      "capacity": 50,
      "latitude": "25.651913",
      "longitude": "-100.290259"
    }
  ]
}
```

With this endpoint you should receive all the venues we have in our Database.

### HTTP Request

`GET http://api.incmty.com/api/v1/venues`

### Query Parameters

Parameter | Description
--------- | -----------
NONE | This endpoint needs no parameters.


### Params Returned

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | string | Venue name
description | text | Venue description, more details about the venue.
capacity | integer | Number of seats.
latitude | float | Venue latitude for geolocalization
longitude | float | Venue longitude for geolocalization