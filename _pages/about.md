---
permalink: /
title: "Baban Gain's Personal Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher at IIT Patna. I work on Natural Language Processing.

{% include base_path %}

{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}
