---
layout: page
title: Calendar and Resources
description: Listing of course modules and topics.
---

# Calendar
<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=Pacific%2FHonolulu&src=bW9tcDA4cHBzNDU3bThybHYxbTM4ZTZhMjhAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&color=%23D50000" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>
{% for module in site.modules %}
{{ module }}
{% endfor %}
