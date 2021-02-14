---
layout: post
title: Identify Customer Segments
category: project
permalink: /projects/Identify-Customer-Segments
display: "/assets/gif"
comments: True
date: 2020-7-14
---

{% assign parent_path = page.path | split:'/' | last %}
{% assign parent_path = page.path | remove:  parent_path %}

{% for file in site.static_files %}
{% if file.path contains parent_path %}
{% assign file_name = file.path | remove:  parent_path | remove:  "/" %}

{% include_relative {{ file_name }} %}

{% endif %}
{% endfor %}