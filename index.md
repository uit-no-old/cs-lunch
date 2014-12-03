---
layout: default
---

The CS-lunch is a seminar series at the Department of Computers Science at the
University of Tromsø. Ph. D. students at the department will present work that 

We are beginning the seminar series in January 2015, and
we're hoping to see you there! 

## Contact 
- Bjørn Fjukstad ([bjorn@cs.uit.no](mailto:bjorn@cs.uit.no))
- Einar Holsbø  ([einar@cs.uit.no](mailto:einar@cs.uit.no))



### News
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

