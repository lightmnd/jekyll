---
layout: page
title: Contact
permalink: /contact/
---

<ul class="list-posts">
  {% for post in site.posts %}
    <li>
      <img src="{{post.image}}">
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname" value="Mickey">
  <br>
  Last name:<br>
  <input type="text" name="lastname" value="Mouse">
  <br><br>
  <input type="submit" value="Submit">
</form> 