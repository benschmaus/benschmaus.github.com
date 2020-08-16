---
layout: post
title: Archive
permalink: /archive
---

Below are posts migrated from an older version of factotumo.com.

{% assign sorted = site.archives | reverse %}
{% for archive in sorted %}
* [{{archive.title}}]({{archive.url}})
{% endfor %}