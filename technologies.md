---
layout: default
permalink: /about/technology
title: Technologies
---

# Our Technology stack

## Programming languages

<p>All our developers have to master Ruby, Ruby on Rails and Javascript ES6 but we really prefer functional programming languages whenever is possible and there is a good use case </p>

<div class="ui internally celled equal width grid">
  {% for technologies in site.data.technology.programming %}
  <div class="row">
    <div class="column">
      <div class="ui center aligned basic centered segment">
        <a href="{{technologies.stack1.link}}">
          <img src="{{technologies.stack1.img}}" class="ui image small" alt="{{technologies.stack1.title}}">
          </a>
      </div>
    </div>
    <div class="column">
      <div class="ui center aligned basic segment">
        <a href="{{technologies.stack2.link}}">
          <img src="{{technologies.stack2.img}}" class="ui image small" alt="{{technologies.stack2.title}}">
         </a>
      </div>
    </div>
    <div class="column">
      <div class="ui center aligned basic segment">
        <a href="{{technologies.stack3.link}}">
          <img src="{{technologies.stack3.img}}" class="ui image small" alt="{{technologies.stack3.title}}">
        </a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<br>
<br>

## Web development and mobile frameworks

<p>Most of our web projects are currently in Ruby on Rails and Elixir Phoenix</p>

<div class="ui internally celled equal width grid">
  {% for technologies in site.data.technology.web %}
  <div class="row">
    <div class="column">
      <div class="ui center aligned basic centered segment">
        <a href="{{technologies.stack1.link}}">
          <img src="{{technologies.stack1.img}}" class="ui image small" alt="{{technologies.stack1.title}}">
        </a>
      </div>
    </div>
    <div class="column">
      <div class="ui center aligned basic segment">
        <a href="{{technologies.stack2.link}}">
          <img src="{{technologies.stack2.img}}" class="ui image small" alt="{{technologies.stack2.title}}">
        </a>
      </div>
    </div>
    <div class="column">
      <div class="ui center aligned basic segment">
        <a href="{{technologies.stack3.link}}">
          <img src="{{technologies.stack3.img}}" class="ui image small" alt="{{technologies.stack3.title}}">
        </a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
