---
layout: post
title: Archive
permalink: /archive
---

Below are posts migrated from an older version of factotumo.com.

{% for archive in site.archives %}
* [{{archive.title}}]({{archive.url}})
{% endfor %}