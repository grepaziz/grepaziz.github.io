---
layout: post
title: "Image Classifier-TF"
category: project
permalink: /projects/Image-Classifier-TF
display: "/assets/gif"
comments: True
date: 2020-6-20
---

{% assign parent_path = page.path | split:'/' | last %}
{% assign parent_path = page.path | remove:  parent_path %}

{% for file in site.static_files %}
{% if file.path contains parent_path %}
{% assign file_name = file.path | remove:  parent_path | remove:  "/" %}

{% include_relative {{ file_name }} %}

{% endif %}
{% endfor %}