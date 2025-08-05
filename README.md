---
layout: single
title: “Aidan Baker”
permalink: /
toc: true           # adds a floating table of contents
---

<div style="text-align:center; margin-bottom:2rem;">
  <img src="/assets/logo.png" alt="Logo" style="width:150px;"/>
  <h1>Hi, I’m Aidan 👋</h1>
  <p><em>Data Scientist passionate about turning data into insights</em></p>
</div>

## 🚀 Experience

XXXX

## 🎓 Education

XXXX

## 💼 Projects

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url | default: project.path }})
<picture>
  <img src="{{ project.image }}" alt="{{ project.title }}" style="max-width:100%;border-radius:8px;"/>
</picture>
**Date:** {{ project.date | date: "%b %e, %Y" }}  
**Categories:** {{ project.categories | join: ", " }}  

{{ project.excerpt }}

- 🔗 [GitHub Repo]({{ project.github | default: "#" }})


## ✉️ Contact

- 📧 your.email@example.com  

---

