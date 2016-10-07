# Schedules

```shell
curl 'http://api.incmty.com/api/v1/schedule?year=2016'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "2.0.6",
    "version": "v1"
  },
  "schedule": [
    {
      "id": 1139,
      "name": "How to build an API",
      "theme_id_refs": 8,
      "sede_id_refs": 69,
      "time_start": "2016-11-18 08:08:00",
      "time_stop": "2016-11-18 09:09:00",
      "venue_id_ref": 263,
      "thumb_img_url": null,
      "large_img_url": null,
      "entity_id_refs": [
        1795
      ],
      "category_id_refs": 7,
      "discover": {
        "size": -1,
        "sort_order": 0
      },
      "hot": false,
      "description": "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quaerat ea debitis nesciunt magnam cupiditate repudiandae, optio laudantium commodi hic quibusdam, molestias, libero quasi pariatur quos unde neque obcaecati dicta..",
      "mobile_description": "How to build an api with your own bare hands and don't get mad in the process.",
      "child_id_refs": 7,
      "website_url": null,
      "twitter_url": null,
      "activity_trend_id_refs": [
        3,
        8
      ]
    },
    {
      "id": 1141,
      "name": "Why Donald Trump s*cks bigtime?",
      "theme_id_refs": 8,
      "sede_id_refs": 69,
      "time_start": "2016-11-18 09:09:00",
      "time_stop": "2016-11-18 10:10:00",
      "venue_id_ref": 263,
      "thumb_img_url": "https://s-media-cache-ak0.pinimg.com/736x/3d/67/6d/3d676d3f7f3031c9fd91c10b17d56afe.jpg",
      "large_img_url": "https://s-media-cache-ak0.pinimg.com/736x/3d/67/6d/3d676d3f7f3031c9fd91c10b17d56afe.jpg",
      "entity_id_refs": [123,12],
      "category_id_refs": 7,
      "discover": {
        "size": 1,
        "sort_order": 0
      },
      "hot": false,
      "description": "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis quaerat ea debitis nesciunt magnam cupiditate repudiandae, optio laudantium commodi hic quibusdam, molestias, libero quasi pariatur quos unde neque obcaecati dicta..",
      "mobile_description": "Why Donald Trump s*cks bigtime? I don't know but i think it's he s*cks, biiiig-time!",
      "child_id_refs": 7,
      "website_url": null,
      "twitter_url": null,
      "activity_trend_id_refs": [
        3,
        8
      ]
    }
  ]
}
```

With this endpoint you should receive all the Schedules we have in our Database.

### Query Parameters

Parameter | Description
--------- | -----------
year      | The year which you want to get the scheduled events.


### HTTP Request

`GET http://api.incmty.com/api/v1/schedule?year=2016`

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | String | Name of the event
theme_id_refs | Integer | Topic id
sede_id_refs | Integer | Sede (place) where event will happen.
time_start | DateTime | Event starts at
time_stop | DateTime | Event ends at
venue_id_ref | Integer | Venue id
thumb_img_url | String | Event thumb Image
large_img_url | String | Event Large Image
entity_id_refs | Array | Array of speaker ids
category_id_refs | Integer | Category Id
discover | Object | EventBase discover params `size` and `sort_order
description | String | Event Description for the Web platform
mobile_description | String | Event Description for the mobile application.
child_id_refs | Integer | Field description not available
website_url | String | Event Webpage information Url
twitter_url | String | Twitter url
hot | Boolean | Indicates a featured event.
activity_trend_id_refs | Array | Activity trend ids a.k.a. 'Recursos del emprendedor'

<aside class="success">
If you're having troubles while connecting with this API please drop us a line!
</aside>
