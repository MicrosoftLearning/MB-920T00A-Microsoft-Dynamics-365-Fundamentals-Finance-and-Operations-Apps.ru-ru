---
title: Размещенные на сервере инструкции
permalink: index.html
layout: home
---

# Каталог содержимого

Гиперссылки на все лабораторные упражнения и демонстрационные видео приведены ниже.

## Лабораторные работы

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Модуль | Лабораторная работа. |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Демонстрации

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Модуль | Демонстрация |
| --- | --- | 
{% for activity in demos  %}| {{ activity.demo.module }} | [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
