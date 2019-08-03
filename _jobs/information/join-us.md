---
title: Join Us
permalink: /join/

lede_markdown: We are a team of passionate, civic-minded professionals who work to bring the principles, values, and practices of the technology sector into government with one goal in mind - improving the lives of Austin's residents.

# DON'T EDIT ANYTHING BETWEEN THE <div> TAGS BELOW!
---


We're currently looking for a [Full Stack Developer](/join/positions/Full-Stack-Developer/) and a [QA Testing & Automation Engineer](/join/positions/QA-testing-engineer/) to work on projects like [alpha.austin.gov](http://alpha.austin.gov/).

Our terms are for 12 months of full-time work (40 hours each week), with opportunities to apply for permanent positions at the city. [Learn about Benefits](/join/information/benefits/)




#### Get Updates
{% include bloomfire-form.html %}


--

<div class="hidden-md hidden-lg hidden-xl" role="menu">
{% assign new_collection = site.collections | where: "title", page.nav_from_collection | first %}
{% assign items = new_collection.docs | sort: "url" | sort: "position" %}
{% assign base_path = page.nav_from_collection | downcase | prepend: "/_" | append: "/"  %}
{% include recursive-nav.html items=items base_path=base_path  %}
</div>
