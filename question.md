---
layout: default
title: Others
permalink: /question/
---

 <div class="home">

  <h4 class="page-heading">Brought to You by <a href="http://www.areteem.org/">Areteem Institute</a> of Witchcraft and Wizardry</h4>

  <ul class="post-list">
    {% for question in site.questions  %}
      <li>
        <!--<span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>-->

        <h3>
          <a class="post-link" href="{{ question.url | prepend: question.baseurl }}">{{ question.title }}</a>
        </h3>
      </li>
    {% endfor %}
  </ul>


  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
