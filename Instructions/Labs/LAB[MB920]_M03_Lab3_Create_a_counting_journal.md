---
lab:
  title: Лабораторная работа 3. Создание инвентарного журнала
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116365"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Модуль 3. Изучение основ Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Задание 3. Создание инвентарного журнала

1. На домашней странице Finance and Operations в правом верхнем углу проверьте, что вы работаете с компанией **USMF**. При необходимости выберите компанию, и в раскрывающемся списке выберите компанию **USMF**.

2. На панели навигации последовательно выберите **Модули** > **Управление запасами** > **Записи журнала** > **Учет номенклатур** > **Инвентаризация**.

3. Нажмите кнопку **+ Новые** в области действий. Откроется диалоговая форма **Создание инвентарного журнала** с кнопкой **ОК** внизу. Нажмите кнопку **ОК**.

4. В форме инвентарного журнала будут отображаться заголовок и подробные сведения

![Снимок экрана: форма инвентарного журнала с заполненными заголовком и подробными сведениями.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Нажмите **Создать строки —&gt; В сети** в области действий.

6. В диалоговом окне **Создание инвентарного журнала наличных запасов** задайте для полей **Склад**, **Статус запасов**, "Место хранения" и **Номерной знак** значение **Да**. 

![Снимок экрана: диалоговое окно "Создание инвентарного журнала наличных запасов" с полями, заполненными как описано.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Разверните раздел **Запись, которую нужно включить** и перейдите по ссылке **Фильтр**. В поле **Код номенклатуры** выберите **A0001** и нажмите **ОК**.

8. Нажмите **ОК** в нижней части диалоговой формы **Создание инвентарного журнала наличных запасов**.

Имеющееся в наличии количество номенклатуры A0001 будет отображаться в разделе **Строки журнала** с разбивкой по местонахождению, складу, месту хранения и номерному знаку.

9. В столбце **Фактический остаток** раздела **Строка журнала** введите значения фактического остатка для местонахождения, склада, места хранения или номерного знака. Следует отметить следующее.

    - Если имеющееся **в наличии** количество совпадет с количеством **фактического остатка**, поле **Количество** будет пустым.

    - Если значение поля **Фактический остаток** будет больше, чем значение поля **В наличии**, поле **Количество** будет содержать положительное значение.

    - Если значение поля **Фактический остаток** будет меньше, чем значение поля **В наличии**, поле **Количество** будет содержать отрицательное значение.

10. Нажмите кнопку **Проверить** в области действий, а затем нажмите кнопку **Опубликовать**.

11. Закройте страницу и вернитесь на домашнюю страницу.