---
title: Инструкции, размещенные в Интернете
permalink: index.html
layout: home
ms.openlocfilehash: f4e2e1489e1997cfd064aa74eb5345e302bb2424
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/27/2022
ms.locfileid: "137910158"
---
# <a name="content-directory"></a>Каталог содержимого

Ниже перечислены гиперссылки на каждую из лабораторных работ и демонстраций.

## <a name="labs"></a>Тестовые службы

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Модуль | Лаборатория |
| --- | --- | 
{% за активность на лабораторных работах  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## <a name="demos"></a>Демонстрационные материалы

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Модуль | Демонстрация |
| --- | --- | 
{% за активность при просмотре демонстрации  %}| {{ activity.demo.module }} | [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
