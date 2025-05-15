---
layout: page
permalink: /
---

# 👋 Welcome!

Hi, I’m Jack Bernard, an undergraduate student at the University of Michigan passionate about digital systems in the built environment, and how technology can shape civic life and community. I'm especially interested in the regulation of digital infrastructures, and the development of civic tech to improve governmental operations, and democracy at large.

- You can learn more about me [here](/about)
- You can learn more about what Urban Technology is [here](/categories/urban-tech/)

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