---
title: Blogs - Table of Contents
subtitle: 
description: 
featured_image: /images/demo/contact.jpg
---

## Linear Algebra, Probability and Statistics

{% assign math_posts = site.posts | where: "categories","math" %}

| Blog | Author |
|----------------|--------|{% for post in math_posts reversed %}
| [{{ post.title }}]({{ post.url }})|{{post.author}} |{% endfor %}

## Machine Learning

{% assign ml_posts = site.posts | where: "categories","ml" %}

| Blog | Author |
|----------------|--------|{% for post in ml_posts reversed %}
| [{{ post.title }}]({{ post.url }})|{{post.author}} |{% endfor %}