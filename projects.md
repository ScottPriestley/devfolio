---
layout: page
title: Projects
permalink: /projects/
---

Below is a list of my public repositories. </br>
These projects focus on new technologies and personal projects.

{% for repo in site.github.public_repositories %}
| **[{{ repo.name | capitalize }}]({{ repo.html_url }})** | {{ repo.description }} | ![Stars](https://img.shields.io/github/stars/{{ site.github.owner_name }}/{{ repo.name }}?style=flat-square) |
{% endfor %}

---
*Note: This list is dynamically updated via the GitHub API.*
