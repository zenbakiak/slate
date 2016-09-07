# INCMTY API doc

To build this documentation you must run:

```shell
$ bundle exec middleman build
```

Then, replase the doc folder inside the public/ directory of the incmty rails application

Be sure to edit the index file and add the `base` tag

```html
  <base href="/doc/">
```

###And that's all!

now you can open:

http://localhost:3000/doc

or

http://api.incmty.com/doc

Create a robots.txt file inside the doc folder with this content:

```
# To ban all spiders from the entire site uncomment the next two lines:
User-agent: *
Disallow: /
```