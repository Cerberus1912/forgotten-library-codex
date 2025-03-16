---
layout: default
title: "Forgotten Library Codex"
---

# 📜 Forgotten Library Codex

Welcome to the Codex of the Forgotten Library. Here you will find records of **those who walk the halls** and **those locked within containment**.

## 🔹 Workers
A collection of individuals who study, document, and protect the Library’s secrets.

<ul>
  {% for worker in site.workers %}
    <li><a href="{{ worker.url | relative_url }}">{{ worker.title }} – {{ worker.codename }}</a></li>
  {% endfor %}
</ul>

## 🔻 Anomalies
A list of mysterious entities, artifacts, and phenomena recorded in the Library.

<ul>
  {% for anomaly in site.anomalies %}
    <li><a href="{{ anomaly.url | relative_url }}">{{ anomaly.title }}</a></li>
  {% endfor %}
</ul>

---
