---
layout: page
title: Guide
permalink: /guide/
---

# Introduction
This guide introduces simple salsa moves with increased difficulty. You can look at it as a game; the more you practice the better you get and the easier the moves get.

Salsa is like Tango in that you would need 2 people to tango: **a leader** and **a follower**. There is no leader without follower and there is no follower without a leader. It is a choice that we make everytime we start dancing with our partner.

# Moves

There are hundreds of moves that professionals use be it on the dancefloor or on stage; they are however all based on a few atomic moves we will address in this guide.

<ul>
  {% assign sorted_tutorials = site.tutorials %}
  {% for tutorial in sorted_tutorials %}
    <li>
      <a href="{{tutorial.url}}">{{ tutorial.title }}</a>
    </li>
  {% endfor %}
</ul>