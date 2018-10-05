---
title: Blog
layout: archive
permalink: /blog/

---

<blockquote class="embedly-card"><h4><a href="https://medium.com/redcrosscbs">RedCrossCBS - Medium</a></h4><p>CBS is an open-source software which allows for monitoring and prevention of disease outbreaks in developing countries. This blog is dedicated to the project and the volunteers who are using information to save lives. Contact us at rebecca.madeleine.bushby@redcross.no.</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'"  %}
{% for year in postsByYear %}
  <h2 id="{{ year.name | slugify }}" class="archive__subtitle">{{ year.name }}</h2>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
