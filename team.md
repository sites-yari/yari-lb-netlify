---
layout: default
permalink: /about/team
title: Team behind the Scene
published: true
---

# Team behind the Scene

<div class="ui four column stackable grid">
  {% for thisAuthor in site.data.team.team limit:2 %}
  <div class="column">
    <div class="ui fluid card">
      <div class="image">
        <img src="{{ thisAuthor.email | to_gravatar }}" alt="Photo of {{ thisAuthor.name }}">
      </div>
      <div class="content" style="background-color: #ffcc00;">
        <div class="header">{{ thisAuthor.name }}</div>
        <div class="meta">
          <span class="date">{{ thisAuthor.desig}}</span>
        </div>
        <div class="description">
          {{ thisAuthor.bio | truncatewords: 15 }}
        </div>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="ui divider" style="margin-top: 30px; margin-bottom: 30px; border-color: #ffcc00;"></div>

<div class="ui four column stackable grid">
  {% for thisAuthor in site.data.team.team offset:2 %}
  <div class="column">
    <div class="ui fluid card">
      <div class="image">
        <img src="{{ thisAuthor.email | to_gravatar }}" alt="Photo of {{ thisAuthor.name }}">
      </div>
      <div class="content" style="background-color: #ffcc00;">
        <div class="header">{{ thisAuthor.name }}</div>
        <div class="meta">
          <span class="date">{{ thisAuthor.desig}}</span>
        </div>
        <div class="description">
          {{ thisAuthor.bio | truncatewords: 15 }}
        </div>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
