---
title: "About"
description: Dive deeper into this project's goals, motivations, successes, and challenges.
permalink: /about.html
layout: page
menus:
  header:
    identifier: about
    skip_title: false
    weight: 2
---

### Children Pages
{% assign menu = site.menus.about %}
{%- for item in menu -%}
* <a href="{{ item.url }}" title="Go to {{ item.title }}"> {{ item.title }}</a>
{% endfor %}

---

# About Us
In early 2020, the Covid-19 pandemic forced all theatres to go dark, leaving
an entire industry without work and without a certain future. It is in this
moment of darkness that the idea of Open Broadway Data is born.

<i class="fas fa-lightbulb" style="color:orange;"></i>
The idea was simple: make historical Broadway data available so that it can
be used to solve the industry's present issues.

<i class="fas fa-lightbulb" style="color:orange;"></i>
We partnered with the [Black Theatre Coalition](https://blacktheatrecoalition.org/)
who wanted to use such data to identify disparities in theatre demographics.

Our team got busy designing and prototyping a solution.
By July that year *(5 months later)*, we had an MVP
([minimum viable product](https://en.wikipedia.org/wiki/Minimum_viable_product))
and began conducting UX (user experience) workshops to better improve our platform.

<div class="warning-msg">
  <i class="fa fa-warning"></i>
  Because our objective now included demographic data, we took extra precautions
  in building our data platform – to protect people's privacy and safety.
</div>

By winter of 2021, *(~12 months after the project started)*, our partners at
BTC were able to use our data platform to present [undeniable evidence
of significant racial disparities within Broadway](/data/data-visualizations.html).

🎉 Using this data as an argument for change, they were able to secure over [30
fully-paid apprenticeships](https://www.broadwayfellows.com/) for black
theatre professionals.

---
### Our decision to archive this project 😢
Our technical requirments for a secure and hardened data platform are
sophisticated – engineering talent for such work is unfortunately in
low supply. As the volume of our sensitive data increased,
our team made the difficult decision that it would be irresponsible to
continue serving our data platform, without further security enhancements.

<i class="fas fa-stop-circle" style="color:red;"></i>
In March 2022 *(roughly 2 years after the project started)*, we took our servers
offline and officially archived the platform.

<i class="fas fa-check-circle" style="color:var(--obd-green);"></i>
You can still access most of this project's data *(except demographic data)*,
through the [Data <i class="fa-solid fa-database"></i>](data.html) section of
this archive site. _Do keep in mind that this data is no longer updated or
maintained._

😢 It is here that this narrative concludes, at least for now.
> If you would like to see this project have a 2nd life, [reach out](about/contact.html) and
we'll see if we have enough momentum to proceed.
