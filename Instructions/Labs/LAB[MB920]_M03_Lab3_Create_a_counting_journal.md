---
lab:
  title: Лабораторная работа 3. Создание инвентарного журнала
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Модуль 3. Изучение основ Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Задание 3. Создание инвентарного журнала

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. На панели навигации последовательно выберите **Модули** > **Управление запасами** > **Записи журнала** > **Учет номенклатур** > **Инвентаризация**.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. В форме инвентарного журнала будут отображаться заголовок и подробные сведения

![Снимок экрана: форма инвентарного журнала с заполненными заголовком и подробными сведениями.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Нажмите **Создать строки —&gt; В сети** в области действий.

6. В диалоговом окне **Создание инвентарного журнала наличных запасов** задайте для полей **Склад**, **Статус запасов**, "Место хранения" и **Номерной знак** значение **Да**. 

![Снимок экрана: диалоговое окно "Создание инвентарного журнала наличных запасов" с полями, заполненными как описано.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. Нажмите **ОК** в нижней части диалоговой формы **Создание инвентарного журнала наличных запасов**.

Имеющееся в наличии количество номенклатуры A0001 будет отображаться в разделе **Строки журнала** с разбивкой по местонахождению, складу, месту хранения и номерному знаку.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - Если имеющееся **в наличии** количество совпадет с количеством **фактического остатка**, поле **Количество** будет пустым.

    - Если значение поля **Фактический остаток** будет больше, чем значение поля **В наличии**, поле **Количество** будет содержать положительное значение.

    - Если значение поля **Фактический остаток** будет меньше, чем значение поля **В наличии**, поле **Количество** будет содержать отрицательное значение.

10. Нажмите кнопку **Проверить** в области действий, а затем нажмите кнопку **Опубликовать**.

11. Закройте страницу и вернитесь на домашнюю страницу.
