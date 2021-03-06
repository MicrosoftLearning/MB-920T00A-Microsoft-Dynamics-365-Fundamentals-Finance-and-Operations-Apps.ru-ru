---
lab:
    title: 'Лабораторная работа 1. Заключительная лабораторная работа по Dynamics 365 Human Resources'
    module: 'Модуль 4. Изучение основ Microsoft Dynamics 365 Human Resources'
---

## Лабораторная работа 1 — заключительная лабораторная работа по Dynamics 365 Human Resources

## Цель

В ходе выполнения этой лабораторной работы вы ознакомитесь с процессом ввода в курс дел нового сотрудника, включая создание записи сотрудника. Также будет рассмотрен процесс аттестации, включающий постановку цели и оценку деловых качеств. Кроме того, вы будете использовать функции самообслуживания для отправки отчета о расходах.

## Исходные условия выполнения лабораторной работы

- **Ориентировочное время выполнения работы**: 20 мин 

## Упражнение 1. Знакомство с управлением персоналом

### Создание записи для нового сотрудника

1. На панели навигации последовательно выберите пункты **Модули** > **Управление персоналом** > **Должности** > **Должности**.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать новую должность.

1. В диалоговом окне **Создание новой должности** откройте меню **Работа** и выберите пункт **Директор магазина**.

1. Нажмите кнопку **Создать должность**.

1. На панели навигации последовательно выберите пункты **Модули** > **Работники** > **Сотрудники**.

1. чтобы создать нового сотрудника, нажмите на панели операций кнопку **+Новые**.

1. На панели **Найм нового работника** введите следующие обновления и нажмите кнопку **Нанять и добавить сведения**.

    | **Настройка** | **Значение** |
    | :--- | :---- |
    | Имя | Илья |
    | Фамилия | Кузнецов |
    | Дата приема сотрудника на работу | Выберите текущую дату|

### Создание цели для нового работника

1. На панели операций нажмите кнопку **Работник**.

1. На вкладке **РАЗВИТИЕ** нажмите кнопку **Цели**.

1. Чтобы увидеть вкладку, возможно, потребуется прокрутить на экране вправо.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать новую цель.

1. На экспресс-вкладке **Общие** введите следующие обновления:

    | **Настройка** | **Значение** |
    | :--- | :---- |
    | Название | Цель — квартальные продажи |
    | Общие сведения | Помощь персоналу магазина в выполнении плана квартальных продаж. |
    | Категория цели | Продажи |
    | Дата начала | Выберите дату, отстоящую на неделю от текущей даты |
    | Дата окончания | Выберите дату, отстоящую на 2 недели от даты начала |

1. На панели операций нажмите кнопку **Сохранить**.

1. Закройте страницу цели квартальных продаж.

1. Закройте страницу целей. | Страница Ильи.

### Назначение учебных курсов новому работнику

1. На странице «Сотрудники» для Ильи, на панели операций нажмите кнопку **Работник**.

1. На вкладке **КОМПЕТЕНЦИИ** нажмите кнопку **Курсы**.

1. Чтобы увидеть вкладку, возможно, потребуется прокрутить на экране вправо.

1. На панели операций нажмите кнопку **+Новые**, чтобы создать новый курс.

1. В представлении сетки, в столбце **Код курса** откройте меню и выберите пункт **00004**.

1. В диалоговом окне **Перенос данных курса** нажмите кнопку **Да**.

1. В столбце **Дата начала** щелкните значок календаря и выберите текущую дату.

1. В столбце **Дата окончания** щелкните значок календаря и выберите дату, отстоящую на две недели от текущей даты.

1. На панели операций нажмите кнопку **Сохранить**.

1. Закройте курсы. | Страница Ильи.

### Создание отчета о расходах

1. На панели навигации последовательно выберите пункты **Модули** > **Управление персоналом** > **Рабочие области** > **Самообслуживание сотрудников**.

1. В разделе **Сведения о моей карьере** на плитке **Расходы** нажмите кнопку **Создать отчет**.

1. На панели **Новый отчет по расходам** откройте меню **Назначение**, выберите пункт **Обучение** и нажмите кнопку **OK**.

1. В сетке **Расходы**, в новой строке расходов введите следующие обновления:

    | **Настройка** | **Значение** |
    | :--- | :---- |
    | Дата проводки | Выберите текущую дату |
    | Категория расходов | Арендная плата за автомобиль |
    | Получатель платежа | LitWare Travel |
    | Сумма проводки | 150,00 |

1. Откройте **Блокнот** на лабораторной виртуальной машине.

1. Введите в Блокноте запись **Квитанция LitWare Travel**.

1. Сохраните файл на рабочем столе под именем **Receipt.txt** и закройте Блокнот.

1. Этот файл вы прикрепите к отчету по расходам в качестве квитанции.

1. Вернитесь в браузере на вкладку Microsoft Dynamics 365 Finance & Operations.

1. На панели операций нажмите кнопку **Поступления заголовка**.

1. На панели **Поступления заголовка** нажмите кнопку **Отправить и вложить новое поступление**.

1. Нажмите кнопку **Обзор**.

1. Выберите файл **Receipt.txt**, созданный вами ранее, и нажмите кнопку **Открыть**.

1. В поле **Примечания** введите **Арендная плата за автомобиль** и нажмите кнопку **Отправить**.

1. Установите флажок **Поступление** и нажмите кнопку **Выбрать строки**.

1. На панели **Прикрепить поступления к строкам** установите флажок **150,00 от LitWare Travel** и нажмите кнопку **OK**.

1. Нажмите кнопку **Закрыть**.

1. На панели операций нажмите кнопку **Рабочий процесс** и выберите **Отправить**.

1. На панели **Отчет по расходам – USMF – Отправить**, в поле **Комментарии** введите **Посмотрите, пожалуйста, мой отчет по расходам**.

1. Нажмите кнопку **Отправить**.

### Запись в журнал показателей производительности

1. На панели навигации последовательно выберите пункты **Модули** > **Управление персоналом** > **Производительность** > **Журнал показателей производительности**

1. На панели операций нажмите кнопку **+Новые**.

1. На странице **Новый журнал** введите следующие обновления.


    | **Настройка** | **Значение** |
    | :--- | :---- |
    | Заголовок | Посещал учебные курсы |
    | Описание | Прошел бизнес-обучение для директоров магазинов |
    | Физическое лицо | Илья Кузнецов |
    | Дата завершения | Текущая дата |

1. На панели операций нажмите кнопку **Сохранить**.

1. На панели операций нажмите кнопку **Добавить в цели**.

1. Выберите **Цель квартальных продаж** и нажмите кнопку **OK**.

1. Закройте страницу журнала показателей производительности.
