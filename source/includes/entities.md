# Entities

```shell
curl 'http://api.incmty.com/api/v1/entities'
  -H 'Authorization: Token token="your_api_key"'
```

> The above command returns JSON structured like this:

```json
{
  "header": {
    "feed_version": "1.0.0",
    "version": "v1"
  },
  "entity": [
    {
      "id": 1547,
      "name": "Chuck Norris",
      "firstname": "Chuck",
      "lastname": "Norris",
      "email": "chuck@mastersoftheuniverse.com",
      "phone_number": "181818181818",
      "facebook": "http://www.facebook.com/chucknorris",
      "twitter": "http://www.twitter.com/chucknorris",
      "linkedin": "http://www.linkedin.com/chuck",
      "biography_spanish": "Norris nació en Ryan, Oklahoma el 10 de marzo de 1940, [6] hijo de Ray Norris y de Wilma Scarberry). Norris ha declarado que tiene raíces irlandesas y Cherokee. Su nombre lo tiene en honor al ministro de su padre, Carlos Berry. Tiene dos hermanos más jóvenes, Wieland (1943-1970; muerto en Vietnam) y Aaron (productor de Hollywood). Cuando Norris tenía dieciséis años, sus padres se divorciaron, trasladándose más tarde con su madre y hermanos a Prairie Village, Kansas, y luego a Torrance, California.",
      "biography_english": "Carlos Ray 'Chuck Norris' (born March 10, 1940) is an American martial artist, actor, film producer and screenwriter. After serving in the United States Air Force, he began his rise to fame as a martial artist, and has since founded his own school, Chun Kuk Do.\nNorris appeared in a number of action films, such as Way of the Dragon, in which he starred alongside Bruce Lee, and was The Cannon Group's leading star in the 1980s.[2][3] He played the starring role in the television series Walker, Texas Ranger from 1993 until 2001. Norris is a devout Christian and politically conservative. He has written several books on Christianity and donated to a number of Republican candidates and causes. In 2007 and 2008, he campaigned for former Arkansas Governor Mike Huckabee, who was running for the Republican nomination for president in 2008.[4] Norris also writes a column for the conservative website WorldNetDaily.\nSince 2005 Norris has been widely associated with an internet meme which documents fictional and often absurd feats associated with him.",
      "review_spanish": "Algo algo",
      "review_english": "Something Something",
      "thumb_img_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/ChuckNorris200611292256.jpg/250px-ChuckNorris200611292256.jpg",
      "large_img_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/ChuckNorris200611292256.jpg/250px-ChuckNorris200611292256.jpg"
    },
    {
      "id": 1820,
      "name": "Bruce Lee",
      "firstname": "Bruce",
      "lastname": "Lee",
      "email": "bruce@email.com",
      "phone_number": "2323232324",
      "facebook": "http://www.facebook.com/brucelee",
      "twitter": "http://www.twitter.com/brucelee",
      "linkedin": "http://www.linkedin.com/brucelee",
      "biography_spanish": "Bruce Lee, nacido como Lee Jun-Fan (San Francisco, California; 27 de noviembre de 1940 - Kowloon, Hong Kong; 20 de julio de 1973), fue un destacado artemarcialista, actor, cineasta, filósofo y escritor estadounidense de origen chino, reconocido en el mundo entero por ser el renovador y exponente de las artes marciales dedicando su vida a dicha disciplina, buscando la perfección y la verdad, llegando a crear su propio método de combate, el Jun Fan Gung-Fu, que tiempo después y sumado a su concepto filosófico se llamaría, el Jeet Kune Do o «el camino del puño interceptor»",
      "biography_english": "Lee Jun-fan (Chinese: 李振藩; November 27, 1940 – July 20, 1973), known professionally as Bruce Lee, was a Hong Kong American actor, martial artist, philosopher, filmmaker,[2] and founder of the martial art Jeet Kune Do. Lee was the son of Cantonese opera star Lee Hoi-Chuen. He is widely considered by commentators, critics, media, and other martial artists to be one of the most influential martial artists of all time,[3] and a pop culture icon of the 20th century.[4][5] He is often credited with helping to change the way Asians were presented in American films.[6]",
      "review_spanish": "Algo sobre bruceleee",
      "review_english": "Something about Bruce",
      "thumb_img_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Bruce_Lee_1973.jpg/220px-Bruce_Lee_1973.jpg",
      "large_img_url": "https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Bruce_Lee_1973.jpg/220px-Bruce_Lee_1973.jpg"
    }
  ]
}
```

With this endpoint you should receive all the Speakers we have in our Database.

### HTTP Request

`GET http://api.incmty.com/api/v1/entities`

Name | Type | Description
-----|------|------------
  id | Integer | Unique Integer
name | String | Speaker's full name
firstname | String | Speaker's firstname
lastname | String | Speaker's lastname
email | String | Email account
phone | String | Phone number
thumb_img_url | String | Image path
large_img_url | String | Image path
twitter_url | String | Twitter account
facebook_url | String | Facebook account
linkedin_url | String | LinkedIn account
biography_spanish | String | Biography in spanish
biography_english | String | Biography in english
review_spanish | String | Review in spanish
review_english | String | Review in spanish