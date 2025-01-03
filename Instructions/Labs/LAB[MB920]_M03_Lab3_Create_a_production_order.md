---
lab:
  title: Лаборатория 3.2. Создание рабочего заказа
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Схема обучения 3. Изучение основ Microsoft Dynamics 365 Supply Chain Management
# Модуль 4. Описание процесса производства

## Лаборатория 3.2. Создание рабочего заказа

## Цель

Производственные заказы помогают инициировать процесс производства в Supply Chain Management. В этом задании вы ознакомитесь с пользовательским интерфейсом и функциональностью формы производственного заказа. Кроме того, вы узнаете, как создать и обработать рабочий заказ к концу упражнения.

## Этапы лабораторной работы

1. На домашней** странице Управления цепочками поставок Dynamics 365 **в правом верхнем углу убедитесь, что вы работаете с компанией **USMF**.

2. При необходимости выберите компанию, и, открыв меню, выберите компанию **USMF**.

3. На левой панели навигации последовательно выберите пункты **Модули** > **Управление производством** > **Производственные заказы** > **Все производственные заказы**.

4. В верхнем меню выберите **новый рабочий порядок** и введите следующие данные.

    - Номер элемента: **D0002**

    - Количество: **10**

    - Сайт: **1**

    - Склад: **11**

    - Доставка: [выберите дату в месяц из сегодняшней даты]

    - Номер BOM: **D0002BOM**

    - Номер маршрута: **000004**

5. Выберите кнопку **Создать**.

Новый рабочий заказ создается для 10 количеств элемента D0002.

6. Выберите **"Рабочий порядок" (меню области действий) &gt; "Оценка процесса &gt; ".**

7. **В диалоговом окне "Оценка**" выберите **"Стандартный**" в **поле "** Параметры прибыли", выберите **поле** "Ссылки" и нажмите **кнопку "ОК**".

Состояние **** рабочего заказа изменится на **"Оценка**".

8. Выберите **"Расписание" (меню области действий) &gt; Рабочие операции расписания заказов &gt; .**

9. **В диалоговом окне "Планирование операций" выберите **"Переадресация"** в **поле "Направление** планирования**" и нажмите кнопку **"ОК**".

10. Выберите **"Вид" (меню панели действий) &gt; "Связанные сведения о резервировании** емкости&gt;".

11. Проверьте новые записи, созданные на **странице резервирования** емкости.

12. Вернитесь на страницу "Все производственные **заказы** ". Обратите внимание, что **состояние** рабочего заказа изменяется на **scheduled**.

13. Выберите **"Рабочий заказ" (меню области действий) &gt; "Выпуск** процесса&gt;".

14. **В диалоговом окне "Выпуск"** выберите **поле** "Ссылки" и нажмите кнопку **"ОК**".

15. Состояние **** рабочего заказа изменится на **"Выпущено**".

16. Выберите **"Рабочий порядок" (меню области действий) &gt; "Запуск** процесса&gt;".

17. **В диалоговом окне "Пуск**" выберите вкладку **"Общие**".

18. На вкладке **"Общие** " введите следующее.

    - Дата: **сегодняшняя дата**

    - Количество: **10**

    - Запуск рабочей среды: **ДА**

    - Теперь карточка маршрута после публикации: **НЕТ**

    - После выбора списка сейчас: **НЕТ**

19. Выберите кнопку **ОК**.

Состояние **** рабочего заказа изменяется на **Started**.

20. Выберите **пункт "Вид " (меню области действий) &gt; Списки** выбора журналов&gt;.

Новый журнал выбора списка создается с тремя строками.

21. Опубликуйте журнал выбора списка.

При необходимости нажмите кнопку **"ОК**  " в окне журнала post.

22. Вернитесь на **страницу "Все производственные заказы**" и выберите **"Вид" (меню области действий) &gt; "Маршрутная карточка** журналов&gt;".

Новый журнал карты маршрута создается с тремя строками.

23. Выберите поле "Операция завершена **" **во всех трех строках и опубликуете журнал карты маршрута.

24. Вернитесь на **страницу "Все производственные заказы" и выберите **"Рабочие заказы**" (меню "Область действий") "Отчет об обработке&gt;" &gt; по завершении**.

25. В диалоговом окне " **Отчет по завершении** " введите **10** в **поле "Хорошее количество** ". **Выберите поле "Конец задания**" и нажмите кнопку **"ОК**".

Состояние **** рабочего заказа изменяется на **"Завершено**". Запасы товара **D0002** увеличиваются на 10 на сайте 1 и складе 11.

26. Выберите "**Управление затратами" (меню "Панель действий") &gt; Сведения о** вычислении представления вычислений&gt;.

Обратите внимание на окончательную стоимость изготовленного элемента на вкладке **"Обзор затрат** ".

 
