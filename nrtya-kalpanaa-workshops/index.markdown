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

You will be given the audio and video of the item. You can use the audio to perform for events.  

You are expected to send video of your performance within a week after the workshop. Individual guidance will be provided based on this video.

You should have at least a basic exposure to Bharata Natyam (or a similar classical dance form) to make the best use of this workshop.  

There is a _Dakshina_ to participate in the workshop, which may vary depending on the item.

Explore the list below to know more about the item.

#### Upcoming Workshops
<ul>
{% capture now %}{{'now' | date: '%s' | plus: 0 }}{% endcapture %}
{% for post in site.posts %}
  {% capture date %}{{post.workshop_date | date: '%s' | plus: 0 }}{% endcapture %}
  {% if date > now %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    {{ post.excerpt }}
  </li>
  {% endif %}
{% endfor %}
</ul>

#### Past workshops
<ul>
{% for post in site.posts %}
  {% capture date %}{{post.workshop_date | date: '%s' | plus: 0 }}{% endcapture %}
  {% if date <= now %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    {{ post.excerpt }}
  </li>
  {% endif %}
{% endfor %}
</ul>

<br/>

---

<br/>
##### Reviews about Workshops


| ------------- |:-------------:|
| How  likely are you to recommend this workshop to a dancer friend   | 9.4 / 10 |
| Lessons were easy to follow   | 9.6 / 10      |
| Item taught is useful | 10 / 10      |
| Online communication was clear | 9.7 / 10  |
| You received individual attention | 9.9 / 10  |

_(Summary of feedback from 14 students, June 2020)_

>Liked your way of teaching...You made sure everyone learned the item and the  one on one meeting to rectify each one's mistake..It was a wonderful experience.. Never thought this would be possible online.

...Sujina Sridharan


>Liked the clarity of explanation . Though virtual we had the experience like being taught in a regular class

...Devija Harikumar

>I really enjoyed the workshop because for me it was a good push and a motivation to get back to dancing and practicing. Even though it was only a 3hr workshop, the item was so well broken into parts and each of the part explained in detail, helping us to be deeply involved in the progress of the pushpanjali.

...Nanda Radhakrishnan

>The class is very helpful and informative. Very well explained about each and every word in the item so that we can dance remembering and understanding the meaning. It is a nice practice item also to improve and control the speed levels. And this is a new experience of being in our own space and dancing.

...Meera Pillai
