---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I'm {{ site.author.firstname }}!<br>
I'm a technical writer passionate about gaming, game hardware, software, and technology. I'm usually chasing the latest gadgets (and am almost always too broke to afford them).
I enjoy learning about coding and seeing how systems tick. I'm a huge Lord of the Rings fan, love traveling and craft beer, and I'm a great team player! 

<p class="text-center">
{% include elements/button.html link="/files/resume.pdf" text="Download my resume!" %}
</p>

<div class="row">
{% include about/skills.html title="Technical Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>