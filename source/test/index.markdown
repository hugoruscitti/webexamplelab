---
layout: page
title: "test"
date: 2012-06-16 22:13
comments: true
sharing: true
footer: true
---

Esta página es una prueba sobre los distintos elementos
sintácticos de octopress.

```
rake "new_post["title"]"
rake "new_page[super-awesome]"
```

Comandos mas usados:

```
rake preview
rake deploy
```


Código fuente:

``` python
import os
print os
``` 

Incluye código fuente:

```
{% include_code [title] [lang:language] path/to/file %}
```

Incluir código:

{% include_code hola.js %}


Imágenes:

{% img http://placekitten.com/890/280 %}
{% img left http://placekitten.com/320/250 Place Kitten #2 %}
{% img right http://placekitten.com/300/500 150 250 Place Kitten #3 %}
{% img right http://placekitten.com/300/500 150 250 'Place Kitten #4' 'An image of a very cute kitten' %}

Frases
------

{% blockquote @allanbranch https://twitter.com/allanbranch/status/90766146063712256 %}
Over the past 24 hours I've been reflecting on my life & I've realized only one thing. I need a medieval battle axe.
{% endblockquote %}


Videos
------

```
{% video url/to/video [width height] [url/to/poster] %}
```
Gist
----

{% gist 996818 %}

