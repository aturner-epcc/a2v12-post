---
layout: section
title: ARCHER2 News and Events
summary: ARCHER2 News and Events
---


{% for post in site.posts %}
<div class="post-area">
  <a href="{{ post.url | prepend: site.baseurl }}" class="bold">{{ post.title }}</a>
  <p class="post-date">{{ post.date | date_to_long_string }}</p>
  <p>
    {{ post.content | strip_html | truncatewords: 50 }}
  </p>
</div>
{% endfor %}



moved to _news

{% for post in site.about.news-events.news %}
<div class="post-area">
  <a href="{{ post.url | prepend: site.baseurl }}" class="bold">{{ post.title }}</a>
  <p class="post-date">{{ post.date | date_to_long_string }}</p>
  <p>
    {{ post.content | strip_html | truncatewords: 50 }}
  </p>
</div>
{% endfor %}




# News and Events

## What's new

[14th October 2019 UKRI Announcement - ARCHER2 Hardware News](./news/191014_ARCHER2_Hardware_news.html)



## Previous News Items

[15th April 2019 UKRI Announcement](./news/190415_UKRI_Announcement.html)