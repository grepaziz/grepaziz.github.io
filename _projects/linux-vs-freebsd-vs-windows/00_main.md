---
layout: post
title: "Linux vs. FreeBSD vs. Windows"
category: project
permalink: /projects/linux-vs-freebsd-vs-windows
display: "/assets/gif"
date: 2020/1/1
updated: 2020/1/2
---

{% assign parent_path = page.path | split:'/' | last %}
{% assign parent_path = page.path | remove:  parent_path %}

{% for file in site.static_files %}
{% if file.path contains parent_path %}
{% assign file_name = file.path | remove:  parent_path | remove:  "/" %}

{% include_relative {{ file_name }} %}

{% endif %}
{% endfor %}