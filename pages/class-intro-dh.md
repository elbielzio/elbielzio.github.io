---
layout: essay-content
title: Class Intro to DH – Fall 2026
permalink: /class-intro-dh.html
show-section-nav: false
---

This section gathers my work for DH 8991-001: Introduction to Digital Humanities (Fall 2026) at the University of Virginia: course materials, assignments and the class digital collection.

## Portfolio

{% assign portfolio = site.essay | where: "part", "course portfolio" | sort: "order" -%}
{% for item in portfolio -%}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}

## Class collection {#collection}

The digital collection built for this class can be explored in several ways:

- [Browse]({{ '/browse.html' | relative_url }})
- [Subjects]({{ '/subjects.html' | relative_url }})
- [Locations]({{ '/locations.html' | relative_url }})
- [Map]({{ '/map.html' | relative_url }})
- [Timeline]({{ '/timeline.html' | relative_url }})
- [Data]({{ '/data.html' | relative_url }})
