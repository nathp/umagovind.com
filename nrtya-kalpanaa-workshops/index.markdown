---
author: umagovind
comments: false
date: 2020-03-08 07:13:19+00:00
layout: page
link: http://umagovind.com/nrtya-kalpanaa-workshops/
slug: nrtya-kalpanaa-workshops
title: Nrtya Kalpanaa series Online workshops
wordpress_id: 341
---


Uma conducts Bharata Natyam workshops online where a new choreography will be taught to interested students.   

Workshops usually last 2 to 3 days, with each session being approx 1 hour and 30 minute duration. These are usually scheduled on weekends.

You will be given the audio and video of the item. You can use the audio to perform the item at venues.

You are expected to send video of your performance within a week after the workshop. Individual guidance will be provided based on this video.

You should have at least a basic exposure to Bharata Natyam (or a similar classical dance form) to make the best use of this workshop.  

There is a _Dakshina_ (fee) to participate in the workshop, which may vary depending on the item.

Explore the list below to know more about the item.

### Upcoming Workshops

{% capture now %}{{'now' | date: '%s' | plus: 0 }}{% endcapture %}
<ul>
{% for post in site.posts %}
  {% capture date %}{{post.workshop_date | date: '%s' | plus: 0 }}{% endcapture %}
  {% if date > now %}
  <li class="workshop excerpt" onclick="location.href='{{ post.url }}'" >
    <span class="workshop-title">{{ post.title }}</span>
    {{ post.excerpt }} more ...
  </li>
  {% endif %}
{% endfor %}
</ul>

### Past workshops
<ul>
{% for post in site.posts %}
  {% capture date %}{{post.workshop_date | date: '%s' | plus: 0 }}{% endcapture %}
  {% if date <= now %}
  <li class="workshop excerpt" onclick="location.href='{{ post.url }}'" >
    <span class="workshop-title">{{ post.title }}</span>
    {{ post.excerpt }} more ...
  </li>
  {% endif %}
{% endfor %}
</ul>

<br/>

---

<br/>
## Feedback of Online Workshops
{% include reviews.html %}
