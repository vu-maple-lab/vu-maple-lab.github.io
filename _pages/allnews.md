---
title: "News"
layout: textlay
excerpt: "Maple Lab at Vanderbilt University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} </p>
<p>- {{ article.headline }}</p>
{% endfor %}
