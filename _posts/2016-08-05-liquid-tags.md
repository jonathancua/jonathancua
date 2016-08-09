---
layout: default
---


<article class="post">

  <h1>{{ page.title }}</h1>

  <div class="entry">
    {{ content }}
  </div>

  <div class="date">
    Written on {{ page.date | date: "%B %e, %Y" }}
  </div>

    Use a variable defined in _config.yaml: {{ site.twitter_username }}

</article>
