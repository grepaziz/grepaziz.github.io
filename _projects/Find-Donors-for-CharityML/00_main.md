---
layout: post
title: "Find Donors for CharityML"
permalink: /projects/Find-Donors-for-CharityML
category: project
comments: True
date: 2020-05-27
---

{% assign parent_path = page.path | split:'/' | last %}
{% assign parent_path = page.path | remove:  parent_path %}

{% for file in site.static_files %}
{% if file.path contains parent_path %}
{% assign file_name = file.path | remove:  parent_path | remove:  "/" %}

{% include_relative {{ file_name }} %}

{% endif %}
{% endfor %}