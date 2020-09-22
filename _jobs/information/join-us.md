---
title: Join Us
permalink: /join/

lede_markdown: We are a team of passionate, civic-minded professionals who work to bring the principles, values, and practices of the technology sector into government with one goal in mind - improving the lives of Austin's residents.

# DON'T EDIT ANYTHING BETWEEN THE <div> TAGS BELOW!
---


Our terms are for 12 months of full-time work (40 hours each week), with opportunities to apply for permanent positions at the city. [Learn about Benefits](/join/information/benefits/)



We are looking for 
* a lead django developer to lead engineering practices for City of Austin’s Office of Design & Delivery [Learn more about the position](https://odd.austintexas.io/join/positions/lead-django-developer/) 
* a mid to senior Full Stack developer to serve on a multidisciplinary project team, with career civil servants, actively demonstrating the value of iterative development and user-centered design. [Learn more about the position](https://odd.austintexas.io/join/positions/Full-Stack-Developer/) 



#### Get Updates
{% include bloomfire-form.html %}


--

<div class="hidden-md hidden-lg hidden-xl" role="menu">
{% assign new_collection = site.collections | where: "title", page.nav_from_collection | first %}
{% assign items = new_collection.docs | sort: "url" | sort: "position" %}
{% assign base_path = page.nav_from_collection | downcase | prepend: "/_" | append: "/"  %}
{% include recursive-nav.html items=items base_path=base_path  %}
</div>
