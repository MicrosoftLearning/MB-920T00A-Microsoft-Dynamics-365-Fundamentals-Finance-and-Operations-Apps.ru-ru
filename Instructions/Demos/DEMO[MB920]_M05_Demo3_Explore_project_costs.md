---
demo:
  title: Демонстрация 3. Знакомство с затратами по проекту
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Демонстрация 3 — знакомство с затратами по проекту

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. В приложении **Dynamics 365 for Finance and Operations**, на панели навигации последовательно выберите пункты **Модули > Управление и учет по проектам > Табели учета рабочего времени > Мои табели учета рабочего времени (оптимизированы для мобильных устройств)** .  
    Для начала отметим, что хотя прямо сейчас мобильное устройство не используется, вы оцените удобство форм для мобильных устройств, когда будет выбран параметр **Мои табели учета рабочего времени (оптимизированы для мобильных устройств)** .

    ![Снимок экрана с меню управления и учета по проектам с выделенными моими табелями учета рабочего времени (оптимизированными для мобильных устройств).](./media/projops_costs_1_select_my_timesheets.png)  

    Данная оптимизация — главная отличительная особенность бизнес-приложений корпорации Майкрософт, и она помогает с минимальным обучением переходить с веб-приложения на приложение для мобильных устройств.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. На странице **Мои табели учета рабочего времени** нажмите кнопку **Создать**.  
    Сейчас создадим новый табель, основанный на заданных параметрах.

1. На панели **Новый табель учета рабочего времени** наведите указатель мыши на поле **Дата**.  
    Вводимая дата определяет период табеля учета рабочего времени.

1. Наведите указатель мыши на пункт **Создать на основе избранного**.  
    Если избранные параметры сохранены, тогда для экономии времени можно выбрать вариант создания на основе избранного.

1. Когда все будет готово, нажмите кнопку **ОК**.

1. На странице **Сведения о моих табелях учета рабочего времени** щелкните значок **Новые +** .

1. На панели **Новая строка табеля учета рабочего времени** наведите указатель мыши на поле **Юридическое лицо**.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. Откройте меню **Код проекта**.

1. Выберите один из доступных проектов, например, проект **Contoso Consulting**.

1. Когда все будет готово, нажмите кнопку **ОК**.  
    Откроется оптимизированный под мобильные устройства экран ввода времени, и можно начать регистрировать свое рабочее время каждый день для проекта и категории, в данном случае **Служба**.

1. На странице **Ввод времени** в поле **Пн** введите **8**.  
    Это значение представляет запись рабочих часов одного дня.

    ![Снимок экрана со страницей ввода времени.](./media/projops_costs_2_mon_box.png)

1. В этой демонстрации дается обзор создания записей времени и расходов, которые будут выставлены по проекту Contoso Consulting.  
    Можно также вводить внутренние и внешние комментарии по проекту, чтобы гарантировать понимание всеми сторонами природы регистрируемого рабочего времени.

1. Рассматриваются записи в форматах, оптимизированных для представления в интернете и на мобильных устройствах, а также показывается, как рабочий процесс используется для управления процедурой утверждения.

1. На панели навигации нажмите кнопку **Сохранить**.

1. В левом меню навигации в разделе **Табели учета рабочего времени** выберите пункт **Мои табели учета рабочего времени**.

1. На странице **Мои табели учета рабочего времени** выберите запись времени, созданную ранее.

1. На вкладке **Табель учета рабочего времени** наведите указатель мыши на столбец «Категория».  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. В разделе **Сведения о строке** наведите указатель мыши на пункты **Внутренний комментарий** и **Внешний комментарий**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. На панели навигации откройте вкладку **Рабочий процесс**.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. На панели **Обзор рабочего процесса табеля учета рабочего времени** нажмите кнопку **Отправить**.

1. На панели **Обзор рабочего процесса табеля учета рабочего времени — Отправка** добавьте любые дополнительные комментарии.

1. Нажмите кнопку **Submit** (Отправить).

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. Находясь на странице **Почасовые проводки**, просмотрите страницу.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

Затем можно подробно рассмотреть проводки ваучера.

1. На панели навигации нажмите кнопку **Ваучер**.

1. На странице **Проводки ваучера** наведите указатель мыши на разделы **Счет ГК** и **Название счета**.  
    В этих разделах можно увидеть влияние на главную книгу, а также счета, которые будут использоваться.  

Сейчас давайте создадим запись расходов для того же самого проекта Contoso consulting.

1. На панели навигации последовательно выберите пункты **Модули > Управление расходами > Мои расходы > Отчеты по расходам**.

1. На странице **Управление расходами**, на вкладке **Отчеты** выберите **+ Новый отчет по расходам**.

1. Проверьте, чтобы в правом верхнем окне выбора компании, к которой подключаетесь, было указано юридическое лицо **USSI**.

1. Щелкните **ОК**.

1. На странице **Расходы** выберите **+ Новый расход**.  
Появится новая строка расходов.

1. В столбце **Категория расходов** выберите пункт **Топливо** в раскрывающемся меню **Категория**.  
Здесь можно ввести новые расходы со сведениями о них.

1. В столбце **Сумма проводки** введите значение **25,00**.

1. В столбце **Валюта** выберите **USD**.

1. Если это не так, измените юридическое лицо на **USSI**.  
    После того, как введены все сведения, можно сохранить расходы.

1. Выберите **Сохранить**.

1. В левом меню навигации в разделе **Рабочие области** выберите пункт **Управление расходами**.

1. На странице **Управление расходами** выберите только что созданный вами отчет по расходам.

1. На странице **Отчет по расходам** выберите поле **Код проекта**, а затем выберите пункт **00000093 Contoso Consulting**.  

Далее можно показать, что плата за топливо выставляется для оплаты по проекту Contoso Consulting, а также увидим дополнительные сведения о расходах.

1. Наведите указатель мыши на поле **Дополнительные сведения**.

1. В правой нижней части экрана нажмите кнопку **Сохранить и продолжить**.

1. В правой части экрана нажмите кнопку **Отправить**.

1. В поле **Комментарий** добавьте любые дополнительные комментарии.

1. Нажмите кнопку **Submit** (Отправить).

1. На странице **Управление расходами** наведите указатель мыши на столбец **Статус утверждения**.  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
