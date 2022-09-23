---
lab:
    title: 'Лабораторная работа 3. Заключительная лабораторная работа по Dynamics 365 Finance'
    module: 'Модуль 2. Изучение основ Microsoft Dynamics 365 Finance'
---

## Лабораторная работа 3 — заключительная лабораторная работа по Dynamics 365 Finance

## Цель

В ходе выполнения этой лабораторной работы вы ознакомитесь с основными возможностями приложения Microsoft Dynamics 365 Finance. Вы исследуете главную книгу путем создания новой сущности, добавления нового счета, значений аналитик и составления пробного баланса. Вы также рассмотрите расчеты с поставщиками путем создания нового поставщика, заказа на покупку и накладной, а затем оплачивая накладную. Наконец, вы проанализируете расчеты с клиентами путем создания нового клиента, накладной и отчета по срокам оплаты, а затем разнося платеж клиента.

## Исходные условия выполнения лабораторной работы

   - **Ориентировочное время выполнения работы**: 45 мин

## Упражнение 1. Знакомство с главной книгой

### Создание нового юридического лица

1. На панели навигации последовательно выберите пункты **Модули** > **Управление организацией** > **Организации** > **Юридические лица**.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать новое юридическое лицо.

1. На панели **Новая сущность** создайте новую сущность, используя следующие сведения, а затем нажмите кнопку **OK**:

    | **Настройка** | **Значение** |
    | :--- | :--- |
    | Название | Contoso Training USA |
    | Компания | USTR |
    | Страна или регион | США |

1. На странице юридических лиц откройте экспресс-вкладку **Адреса** и выберите пункт **Правка**.

1. На информационной панели введите следующие обновления и нажмите кнопку **OK**:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Почтовый индекс| 98052|
    | Улица| 123 Main Street (Мейн-стрит)|
    | Основной для страны или региона | Убедитесь, что выбрано значение **Да**. |

1. Откройте экспресс-вкладку **Контактные данные**.

1. Нажмите кнопку **+Добавить** и введите следующие контактные данные:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Описание| Основной офис|
    | Контактный телефон или адрес| 888-555-1234|
    | Основной| Установите флажок. |

1. Откройте экспресс-вкладку **Налоговая регистрация**.

1. В поле **Налоговый регистрационный номер** введите **88-1234567**.

1. На панели операций нажмите кнопку **Сохранить**.

1. На панели навигаций нажмите кнопку **Главная**.

### Создание нового счета в существующем плане счетов

1. На домашней странице в правом верхнему углу проверьте, чтобы была выбрана компания **USMF**.  
    Если это не так, выберите в списке текущую компанию, а затем замените ее на **USMF**.

1. На панели навигации последовательно выберите пункты **Модули** > **Главная книга** > **План счетов** > **Счета** > **Счета ГК**.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать новый счет доходов.

1. На странице «Счета ГК» введите следующие обновления.

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Счет ГК| 401500|
    | Название| Доход от обучения|
    | Тип счета ГК| Доход |

1. На панели операций нажмите кнопку **Сохранить**.

### Добавление нового значения аналитики

1. На панели навигации последовательно выберите пункты **Модули** > **Главная книга** > **План счетов** > **Аналитики** > **Финансовые аналитики**.

1. В списке навигации выберите пункт **СтрокаУслуг**.  
    Можно также воспользоваться полем **Фильтр** для поиска пункта **СтрокаУслуг**.

1. На панели операций нажмите кнопку **Значения аналитик**.

1. На панели операций нажмите кнопку **+Новые**.

1. В поля **Значение аналитики** и **Описание** введите **Услуги по обучению**.

1. На панели операций нажмите кнопку **Сохранить**.

### Использование счета и значения аналитики в главной книге

1. На панели навигации последовательно выберите пункты **Модули** > **Главная книга** > **Записи журнала** > **Общие журналы**.

1. На панели операций нажмите кнопку **+Новые**.

1. В первой строке списка, в столбце **Имя** откройте меню и выберите пункт **Общий журнал**.

1. На панели операций нажмите кнопку **Строки**.

1. В списке, в столбце **Дата** щелкните значок календаря и измените дату на 1-е число месяца.

1. В столбце **Счет** откройте меню и введите следующие обновления:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | СчетГК| 601200|
    | Подразделение| 004|
    | Отдел| 025|
    | ЦентрЗатрат| 009|
    | НоменклатурнаяГруппа| Службы|

1. Введите в поле **Описание** значение **Реклассификация затрат**.

1. Введите в поле **Дебет** значение **1000,00**.

1. Прокрутите на экране вправо и в столбце **Корреспондирующий счет** откройте меню и введите следующие обновления:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | СчетГК| 602200|
    | Подразделение| 004|
    | Отдел| 025|
    | ЦентрЗатрат| 009|
    | НоменклатурнаяГруппа| Службы|

1. На панели операций нажмите кнопку **Сохранить**.

1. На панели операций последовательно выберите **Проверить** > **Проверить**.  
    Дождитесь завершения проверки журнала.

1. Ознакомьтесь с баннером предупреждения.  
    В данной лабораторной работе это предупреждение можно проигнорировать.

1. На панели операций нажмите кнопку **Разнести**.

### Составление пробного баланса с помощью набора аналитик

1. На панели навигации последовательно выберите пункты **Модули** > **Главная книга** > **Запросы и отчеты** > **Пробный баланс**.

1. На странице пробного баланса нажмите кнопку **Рассчитать сальдо**.

1. Кнопка **Рассчитать сальдо** располагается под настройками **ДАННЫЕ, КОТОРЫЕ СЛЕДУЕТ ВКЛЮЧИТЬ**.

1. Просмотрите результаты в таблице.

1. На странице пробного баланса в разделе **Стандартное представление** разверните список **Параметры**.

1. В разделе **ДАННЫЕ, КОТОРЫЕ СЛЕДУЕТ ВКЛЮЧИТЬ** откройте меню **Набор финансовых аналитик** и выберите пункт **СчГК-Под-ОТД-ЦЗ**.

1. Нажмите кнопку **Рассчитать сальдо**, чтобы просмотреть используемые в журнале аналитики.

1. Закройте страницу.

## Упражнение 2. Знакомство с расчетами с поставщиками

### Создание поставщика

1. На панели навигации последовательно выберите пункты **Модули** > **Расчеты с поставщиками** > **Поставщики** > **Все поставщики**.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать поставщика.

1. На странице «Новая запись» создайте нового поставщика, используя следующие сведения:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Счет поставщика| V00001|
    | Название| Корпорация ABC Training|
    | Группа| 20|

1. На панели операций нажмите кнопку **Сохранить**.

1. Откройте экспресс-вкладку **Адреса** и выберите команду **+Добавить**.

1. На панели «Новый адрес» введите следующие обновления и нажмите кнопку **OK**:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Имя или описание.| Основной офис|
    | Почтовый индекс| 98052|
    | Улица| 123 Front Street (Франт-стрит)|

1. На панели операций нажмите кнопку **Сохранить**.

1. Откройте экспресс-вкладку **Платеж**.

1. Откройте меню **Способ оплаты** и выберите пункт **ЧЕК**.

1. Откройте экспресс-вкладку **Налог 1099** и введите следующие обновления:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Отчет 1099| Да|
    | Код плательщика федерального налога| 82–1234567|
    | Тип кода налогоплательщика| Идентификационный номер работодателя|
    | Ячейка 1099| MISC-03|

1. На панели операций нажмите кнопку **Сохранить**.

1. Закройте форму.

### Создание заказа на покупку для нового поставщика

1. В счете V00001: На странице корпорации ABC Training, на панели операций нажмите кнопку **Закупки**.

1. На вкладке **НОВЫЕ** панели операций нажмите кнопку **Заказ на покупку**.

1. На странице «Заказ на покупку» в разделе **Строки заказа на покупку** введите следующие обновления:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Номер номенклатуры| S0001|
    | Количество| 2|

    >[!ПРИМЕЧАНИЕ] Чтобы увидеть столбец **Количество**, возможно, потребуется прокрутить на экране вправо.

1. На панели операций нажмите кнопку **Сохранить**.

1. На панели операций нажмите кнопку **Покупка**, и на вкладке **ОПЕРАЦИИ** нажмите кнопку **Подтвердить**.

### Запись накладной поставщика для заказа на покупку

1. На панели операций нажмите кнопку **Накладная**.

1. На вкладке **ФОРМИРОВАНИЕ** нажмите кнопку **Накладная**.

1. На панели операций нажмите кнопку **По умолчанию из**: **Количество поступающих продуктов**.

1. В меню **Количество по умолчанию для строк** выберите пункт **Заказанное количество** и нажмите кнопку **OK**.

1. На странице «Накладная поставщика» введите следующие обновления:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Номер| INV001|
    | Описание накладной| Услуга по первоначальной установке|
    | Дата накладной| *введите текущую дату*|

1. На панели операций нажмите кнопку **Сохранить**.

1. На панели операций нажмите кнопку **Обновить статус сопоставления**.

1. На панели операций нажмите кнопку **Разнести**.

### Оплата накладной поставщика

1. На панели навигации последовательно выберите пункты **Модули** > **Расчеты с поставщиками** > **Платежи** > **Журнал платежей поставщикам**.

1. На панели операций нажмите кнопку **+Новые**.

1. На странице «Журнал платежей поставщикам», в первой строке, в столбце **Имя** откройте меню и выберите пункт **ПлатПостав**.

1. На панели операций нажмите кнопку **Строки**, чтобы записать платеж.

1. На странице «Платежи поставщикам» в поле **Счет** введите **V00001**.

1. На панели инструментов нажмите кнопку **Сопоставление проводок**.

1. На странице сопоставления проводок для корпорации ABC Training в столбце **Метка** установите флажок.

1. В правом нижнем углу экрана нажмите кнопку **OK**.

1. На панели операций нажмите кнопку **Создание платежей**.

1. На панели **Создание платежей** введите следующие обновления и нажмите кнопку **OK**:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Способ оплаты| ЧЕК|
    | Банковский счет| USMF OPER|

1. На панели **Оплата чеком** просмотрите сведения и нажмите кнопку **OK**.

    >[!ПРЕДУПРЕЖДЕНИЕ] Выводится сообщение об ошибке **Не удается найти принтер с путем**. Это предупреждение следует проигнорировать. В лабораторной работе принтер не устанавливается.

1. Прокрутите на экране вправо и убедитесь, что в столбце **Статус платежа** отображается значение **Отправлено**.

1. На панели операций последовательно выберите **Проверить** > **Проверить**.

1. На панели операций нажмите кнопку **Разнести**.

## Упражнение 3. Знакомство с расчетами с клиентами

### Создание клиента

1. На панели навигации последовательно выберите пункты **Модули** > **Расчеты с клиентами** > **Клиенты** > **Все клиенты**.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать клиента.

1. На панели **Создание клиента** создайте нового клиента, используя следующие сведения, а затем нажмите кнопку **Сохранить**:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Счет клиента| US-901|
    | Название| Fabrikam Consulting Services|
    | Группа клиентов| 30|
    | Почтовый индекс| 98052|
    | Улица| 123 Middle Street (Мидл-стрит)|

1. На странице компании Fabrikam Consulting Services, имеющей счет US-901, откройте экспресс-вкладку **Значения платежа по умолчанию**.

1. Откройте меню **Способ оплаты** и выберите пункт **ЧЕК**.

1. Откройте экспресс-вкладку **Финансовые аналитики**.

1. Введите в поле **Подразделение** значение **004**.

1. На панели операций нажмите кнопку **Сохранить**.

### Создание для нового клиента накладной с произвольным текстом

1. На панели операций нажмите кнопку **Накладная**, и на вкладке **НОВЫЕ** нажмите кнопку **Накладная с произвольным текстом**.

1. На странице компании Fabrikam Consulting Services, имеющей счет US-901, в разделе **Накладная с произвольным текстом** – **заголовок** установите для даты **НАКЛАДНОЙ** текущую дату.

1. В разделе **Строки накладной** внесите следующие изменения:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Описание| Обучение от компании Consultant Service|
    | Счет ГК| 401200|
    | Налоговая группа номенклатур| WA|
    | Сумма| 1500,00|

1. На панели операций нажмите кнопку **Налог с продаж**.

1. На странице «Налоговые проводки» просмотрите запись и нажмите кнопку **OK**.

1. На панели операций нажмите кнопку **Разнести**.

1. На панели **Разноска накладной с произвольным текстом** в разделе **ПАРАМЕТРЫ ПЕЧАТИ** установите переключатель **Печать накладной** в положение **Да** и нажмите кнопку **OK**.

1. На панели **Настройки назначения печати** нажмите кнопку **OK**, чтобы вывести накладную на экран.

1. Просмотрите накладную и, завершив просмотр, закройте накладную.

1. Закройте форму.

### Формирование отчета по срокам оплаты расчетов с клиентами в целях проверки

1. На панели навигации последовательно выберите пункты **Модули** > **Кредит и коллекции** > **Запросы и отчеты** > **Клиенты** > **Отчет по срокам оплаты по клиентам**.

1. На панели **Отчет по срокам оплаты по клиентам** введите следующие обновления и нажмите кнопку **OK**:

    | **Настройка**| **Значение**|
    | :--- | :--- |
    | Распределение по срокам оплаты на дату| Текущая дата|
    | Определение периода распределения по срокам| 30_60_90_180|
    | Сведения| гг.|

1. В отчете по срокам оплаты по клиентам щелкните стрелку вниз **Следующая страница** и прокрутите экран до последней страницы.
    Просмотрите накладную, созданную для клиента US-901.

1. Закройте форму.

### Разноска платежа клиента для накладной с произвольным текстом

1. На панели навигации последовательно выберите пункты **Модули** > **Расчеты с клиентами** > **Платежи** > **Журнал платежей клиентов**.

1. На панели операций нажмите кнопку **+Новые**.

1. На странице «Журнал платежей клиентов» в столбце **Имя** откройте меню и выберите пункт **ПлатКлиент**.

1. На панели операций нажмите кнопку **Ввод платежей клиента**.

1. Введите в поле **Клиент** значение **US-901**.  
    Дождитесь загрузки данных и установите флажок в столбце **Метка**.

1. Над сеткой в поле **Сумма** введите **1597,50**. Сумма, показываемая в поле **Оставшаяся сумма**, должна автоматически измениться с **1597,50** на **0**.  
    Возможно, для расчета значения потребуется выделить пустую область.

1. В поле **Ссылка на платеж** введите значение **Чек# 123**.

1. На панели операций нажмите кнопку **Сохранить в журнале**.

1. Закройте форму.

1. На панели операций нажмите кнопку **Строки**.

1. На панели операций последовательно выберите **Проверить** > **Проверить**.

1. На панели операций нажмите кнопку **Разнести**.