---
layout: page
title: Posts
---

## internet

<ul>
{% for post in site.categories.internet %}
<li>
  <a href="{{ post.url }}">{{post.title}}</a> / {{post.date | date_to_string}}
</li>
{% endfor %}
</ul>

## security

<ul>
{% for post in site.categories.security %}
<li>
  <a href="{{ post.url }}">{{post.title}}</a> / {{post.date | date_to_string}}
</li>
{% endfor %}
</ul>

## business

<ul>
{% for post in site.categories.business %}
<li>
  <a href="{{ post.url }}">{{post.title}}</a> / {{post.date | date_to_string}}
</li>
{% endfor %}
</ul>

## local

<ul>
{% for post in site.categories.local %}
<li>
  <a href="{{ post.url }}">{{post.title}}</a> / {{post.date | date_to_string}}
</li>
{% endfor %}
</ul>

## misc

<ul>
{% for post in site.categories.misc %}
<li>
  <a href="{{ post.url }}">{{post.title}}</a> / {{post.date | date_to_string}}
</li>
{% endfor %}
</ul>
