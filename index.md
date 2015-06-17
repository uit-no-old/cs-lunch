---
layout: default
---

The CS-lunch is a seminar series at the Department of Computers Science at the
University of Tromsø. Ph. D. students at the department will present their
accepted conference and journal papers for both academic staff and students.


The next CS-lunch will be fall 2015. 


### Latest News
  <ul class="post-list">
    {% for post in site.posts limit:3 %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
