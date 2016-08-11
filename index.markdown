---
layout: page
title: Rúben Sousa
---
I'm a student of Telecommunications and Informatics at University of Minho hoping to finish my master's degree on 2017.
I'm also a part-time Android developer freelancer.

I spend a lot of my free time developing some projects in Android and Java, some of which are open source and available on my GitHub account:
[https://github.com/rubensousa](https://github.com/rubensousa)

You can also find my Android apps in Google Play: [https://play.google.com/store/apps/developer?id=rubensousa](https://play.google.com/store/apps/developer?id=rubensousa)

This is my personal blog, where I'll be posting content related to software engineering.

### Stuff that I'm currently learning

- Android testing (Espresso and JUnit tests)
- Dependency injection with Dagger2

## Recent articles

{% for post in site.posts limit:4 %}
<li class="c-archives__item">
            <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
            <p>{{ post.date | date: "%b %-d, %Y" }}</p>
              <div>{{ post.content |truncatehtml | truncatewords: 30 }}</div>
        </li>
{% endfor %}