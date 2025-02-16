---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

$\ast$ for equal contribution

{% include base_path %}

<h3>2025</h3>

{% for post in site.publications reversed %}
  {% if post.year contains "2025" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h3>2024</h3>

{% for post in site.publications reversed %}
  {% if post.year contains "2024" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h3>2023</h3>

{% for post in site.publications reversed %}
  {% if post.year contains "2023" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h3>2022</h3>

{% for post in site.publications reversed %}
  {% if post.year contains "2022" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
