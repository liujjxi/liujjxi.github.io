---
layout: page
title: Hello World!
tagline: Supporting tagline
---

# index

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:

```text
title : My Blog =)

author :
  name : Name Lastname
  email : blah@email.test
  github : username
  twitter : username
```

The theme should reference these variables whenever needed.

## Sample Posts

This blog contains sample posts which help stage pages and blog data. When you don't need the samples anymore just delete the `_posts/core-samples` folder.

```text
$ rm -rf _posts/core-samples
```

Here's a sample "posts list".

*  {% for post in site.posts %}
* {{ post.date \| date\_to\_string }} » [{{ post.title }}](https://github.com/liujjxi/liujjxi.github.io/tree/42ddfd2029b148eaaac9b30ee4058b1ad8fb4813/%7B%7B%20BASE_PATH%20%7D%7D%7B%7B%20post.url%20%7D%7D)
*  {% endfor %}

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)! We need to clean up the themes, make theme usage guides with theme-specific markup examples.

