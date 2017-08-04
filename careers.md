---
layout: post
title: Careers
permalink: /about/careers
date:   2017-08-01 00:00:00 +0530

---

<div class="ui grid stackable">

    <div class="column ten wide">
      <p>

      </p>
      <p>
      At {{ site.title }} we work in a relaxed and motivating environment. We
      love to learn and use modern and efective technologies. We follow the code of the
      Agile Samurai! We always strive for a culture of continuous learning.      </p>

      <strong>The benefits of working with us includes:</strong>
      <ul>
        <li class="item">Work with Brilliant People</li>
        <li class="item">Learn and build with Leading Edge Technologies</li>
        <li class="item">Build great products and solve meaningful problems</li>
        <li class="item">Work remotely 2 or 3 days per week</li>
      </ul>



      <div class="ui hidden big divider"></div>

      {% assign vacancies = site.pages | where: "ptype", "career" %}

      <h2>Open Positions</h2>
      <p>
      The ideal candidate is able to rapidly build high-quality Mobile
      and/or Web applications and has an excellent knowledge of open source
      technologies and programming languages. A very good knowledge
      of HTML, CSS, SQL and Unix based operating systems and one of
      these programming languages: Elixir, Ruby, Elm, Javascript.
      </p>
      <div class="ui middle bulleted aligned animated list">
        {% for post in vacancies %}
          <div class="item"><a href="{{ post.url }}">{{ post.title }}</a></div>
        {% endfor %}
      </div>

      <h2>How to Apply?</h2>
      <p>If you're applying for a developer position, then there is an easy way
      for you to apply. Check <a href="https://github.com/realyarilabs/join-us.git">this GitHub Repo</a> </p>
      <ul>
       <li>Fork <a href="https://github.com/realyarilabs/join-us.git">this repository.</a></li>
       <li>Read questions in `questions.md`</li>
       <li>Create a new file, name it `answers.md`</li>
       <li>Submit a `Pull Request` once you're finish with all the questions.</li>
      </ul>



    </div>
    <div class="column six wide">
      <img src="/assets/img/lightrains-team.jpg" alt="{{ site.title }} Team" class="ui image lazy fluid" />
      <div class="ui hidden divider"></div>
      {% include contact-detail.html %}
      <br>
    </div>

  </div>
