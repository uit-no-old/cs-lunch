---
layout: default
---

The CS-lunch is a seminar series at the Department of Computers Science at the
University of Tromsø. Ph. D. students at the department will present their
ongoing work for both academic staff and students. It is an open seminar where
we wish to include all of the different research groups at the department.  

We are beginning the seminar series in January 2015, and we're hoping to see you
there! 



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
