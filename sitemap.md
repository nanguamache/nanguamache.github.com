---
# Remember to set production_url in your _config.yml file!
title : 网站地图
---
{% for page in site.pages %}
* [{{ page.title }}]( {{site.production_url}}{{ page.url }} ){% endfor %}
{% for post in site.posts %}
* [{{ post.title }}]( {{site.production_url}}{{ post.url }} ){% endfor %}
