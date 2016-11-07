---
layout: page
title: US Corruption
tagline: Exposing All Levels of Government Corruption
---
{% include JB/setup %}
## [Please help contribute!](https://github.com/uscorruption/uscorruption.github.io)


This website uses standard markdown as well as HTML, meaning you can copy your Reddit post and commit it.

I'd like to ultimately make a release daily, but that depends on how busy the commits are coming in and any merging issues we run into.

When making a new file, place it in the `_posts` folder and follow the naming conventions:

`YYYY-MM-DD-Post-title.md`

Include this in the top of the file, replacing information as necessary.

    ---
    layout: post
    categories: Assange
    title: Assange is Dead, March on DC
    tagline: Assange Outlines Treason
    tags: [Assange, WikiLeaks, FBI, Clinton]
    ---

Simply begin your post on the line below the final set of dashes.

_____

### Current Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
