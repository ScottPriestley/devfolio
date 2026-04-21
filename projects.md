---
layout: page
title: Projects
permalink: /projects/
---

Below is a curated list of my public repositories. These projects focus on technical automation, enterprise integrations, and specialized engineering disciplines.

| Project Name | Description | Status |
| :--- | :--- | :--- |
{% for repo in site.github.public_repositories %}
| **[{{ repo.name | capitalize }}]({{ repo.html_url }})** | {{ repo.description }} | ![Stars](https://img.shields.io/github/stars/{{ site.github.owner_name }}/{{ repo.name }}?style=flat-square) |
{% endfor %}

---
*Note: This list is dynamically updated via the GitHub API.*
