---
lab:
  title: Лабораторная работа 4. Создание производственного заказа
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>Задание 4. Создание производственного заказа

## <a name="objectives"></a>Задачи

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

Вам необходимо создать новый производственный заказ для своей компании.

## <a name="lab-setup"></a>Исходные условия выполнения лабораторной работы

   - **Примерное время**: 5 минут

## <a name="instructions"></a>Инструкции

1. На домашней странице Finance and Operations проверьте в правом верхнем углу, что вы работаете с компанией USMF.

1. При необходимости выберите компанию, и, открыв меню, выберите компанию **USMF**.

1. На левой панели навигации последовательно выберите пункты **Модули** > **Управление производством** > **Производственные заказы** > **Все производственные заказы**.

1. В меню вверху выберите **Новый производственный заказ**.

1. В разделе **ИДЕНТИФИКАЦИЯ** введите в поле **Номенклатурный номер** значение **D0001** и выберите идентифицированную номенклатуру.

1. В разделе **ПРОИЗВОДСТВО** в поле **Поставка** выберите дату, отстоящую от текущей даты на один месяц.  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. Введите в поле **Количество** значение **20**.

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![Экранное изображение, отображающее заполненную область «Создание производственного заказа»](./media/lp1-m4-new-production-order-pane.png)

1. Нажмите кнопку **создания**.
