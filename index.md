---
layout: page
permalink: /
---

# Welcome

Hi, I’m Jack Bernard, an undergraduate student at the University of Michigan passionate about digital systems and their role in civic life and community.
This site contains my blog, previous work, thoughts, and experiments.

> *Technology with a thoughtful, defined purpose... Technotion*

![City](/assets/img/chicagobusy.jpg "Busy Chicago Cityscape, 2024"){: width="900"}

***

## Featured Posts

- [What is Urban Technology? (v1)](/posts/What-is-Urban-Technologyv1/)
- [The State of Urban Technology w/ Siqi Zhu](/posts/The-State-of-Urban-Tech-feat-Siqi-Zhu/)

## Featured Projects

- [projection_future() - Interactive Media Installation (Writeup Coming Soon!)](https://technotion-us.github.io/)
- [Smart Home Installation w/ Home Assistant (Writeup Coming Soon!)](https://technotion-us.github.io/)

## Recent Posts

<ul>
  {% for post in site.posts limit:20 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>