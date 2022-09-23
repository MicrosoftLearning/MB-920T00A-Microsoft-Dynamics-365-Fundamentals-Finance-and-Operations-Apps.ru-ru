---
lab:
  title: Лабораторная работа 2. Создание заказа на покупку
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Модуль 3. Изучение основ Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>Задание 2. Создание заказа на покупку

## <a name="objectives"></a>Задачи

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>Исходные условия выполнения лабораторной работы

   - **Примерное время**: 10 мин

## <a name="instructions"></a>Инструкции

1. На домашней странице Finance and Operations проверьте в правом верхнем углу, что вы работаете с компанией USMF.

1. При необходимости выберите компанию, и, открыв меню, выберите компанию **USMF**.

1. В левом верхнем углу нажмите кнопку вызова меню **Развернуть панель навигации**.

1. Выберите последовательно пункты **Модули** > **Закупки и поиск источников** > **Заказы на покупку** > **Все заказы на покупку**.

1. На странице «Все заказы на покупку» в верхнем меню выберите пункт  **+ Новые**.

1. На панели Создание заказа на покупку откройте меню **Счет поставщика** и выберите пункт **US-101**.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. Разверните раздел **Общие**.

1. В разделе **АНАЛИТИКИ ХРАНЕНИЯ** откройте меню **Сайт** и просмотрите список сайтов.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. В разделе **ДАТЫ** в поле «Дата поставки» указывается, когда должны быть поставлены закупленные товары и услуги.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. Чаще всего заказы на покупку создаются автоматически в результате сводного планирования, прямой поставки и при выполнении других процессов.

1. Щелкните **ОК**.

1. При создании вручную заказ на покупку обычно создается агентом по закупкам.

    ![Экранное изображение, показывающее местоположение меню заголовка](./media/lp1-m3-purchase-order-header-option.png)

1. В меню раздела **Строки заказа на покупку** выберите пункт **Строка заказа на покупку**.

    ![Экранное изображение, показывающее местоположение пункта меню «Строка заказа на покупку»](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. В разделе **ПОКАЗАТЬ** выберите пункт **Аналитики**.

1. Создайте заказ на покупку, используя компанию USMF.

1. На панели Отображение аналитик в разделе **АНАЛИТИКИ ПРОДУКТА** установите флажок **Цвет**.

1. Необязательно: Если установлен переключатель «Сохранить настройки», при последующем открытии заказа на покупку отобранные аналитики также будут отображаться на сетке строк заказа.

1. Щелкните **ОК**.

1. Откройте меню ячейки **Номенклатурный номер** и выберите значение **T0004**.

1. Помните, вместо прокрутки списка можно также ввести значение в поле фильтра.

1. Строки заказа для продуктов и услуг создаются путем указания номенклатурного номера либо как расходы посредством определения категории закупаемой продукции.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. Откройте меню **Цвет**, просмотрите доступные варианты, а затем выберите один из цветов или одну из комбинаций цветов.

1. Поля «Сайт» и «Склад» обычно заполняются значениями из заголовка заказа, но можно переопределить поля, если для некоторых строк поставка выполняется в другие места.

1. Введите в поле **Количество** значение **10**.

1. Поле «Количество» автоматически заполняется минимальным количеством по заказу продукта, если эта настройка задана, или значением 1.

1. Дополнительные сведения:

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. Под строками заказа на покупку, внизу страницы нажмите кнопку **Сведения о строке**.

1. Перейдите на вкладку **Поставка**.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. Закройте страницу строки заказа на покупку.

1. Воспользуйтесь на странице «Все заказы на покупку» функцией фильтра и найдите свой новый заказ на покупку.

1. Завершив выполнение лабораторной работы, закройте страницу «Все заказы на покупку» и вернитесь на домашнюю страницу.
