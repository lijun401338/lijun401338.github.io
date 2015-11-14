---
layout: index
---

## Contents

### test
{% for post in site.categories.test %}
* [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}
Sometimes you want bullet points:

* Start a line with a star
* Profit!
