---
layout: default
title: News Room
---

<ul>
    {% for post in site.posts %}
      <li class="space-y-1">
        <h3 class="text-black mb-4">{{ post.title }}</h3>
        <p style="margin-top: -.5rem;">{{ post.author }}</p>
        <p class="text-gray-500">{{ post.source }}</p>
        <a href="{{ site.baseurl }}{{ post.url }}">Read More ></a>
      </li>
    {% endfor %}
  </ul>