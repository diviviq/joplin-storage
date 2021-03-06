Мужчина, pause on caught exceptions

Поговорим о практическом применении одной очень интересной темы — системного мышления.

Принципов и методов в системном мышлении много, очень рекомендую почитать соответствующую литературу. Например, простую и интересную [книгу](https://www.litres.ru/dzhozef-o-konnor-3/iskusstvo-sistemnogo-myshleniya-neobhodimye-znaniya-o-s/?utm_medium=cpc&utm_source=google&utm_campaign=Tovarnaya1%7C184350330&utm_term=&utm_content=k50id%7Cpla-354311702308%7Ccid%7C184350330%7Caid%7C43672117890%7Cgid%7C9065790330%7Cpos%7C1o1%7Csrc%7Cg_%7Cdvc%7Cc%7Creg%7C1011874%7Crin%7C%7C&k50id=9065790330%7Cpla-354311702308&gclid=Cj0KCQiA1sriBRD-ARIsABYdwwGUE11nAgsCfIFEY1XuRqx8VvjoQ-QDczYJF7Pw2aobTu907N3fdfMaAmT0EALw_wcB). Сегодня мы затронем только один принцип — эмерджентные, или возникающие свойства систем.

Расскажу и о теории, и, главное — о практических аспектах применения. В нашей жизни — программистов, внедренцев, архитекторов, аналитиков и руководителей проектов.

Сначала, тем не менее, немного теории.

#### Системы и свойства

На работе мы почти всегда имеем дело с системами — сложными совокупностями людей, процессов, отношений (формальных и неформальных), явных и скрытых лидеров, материальных объектов, информационных систем, клиентов, поставщиков, оборудования, и т.д., до бесконечности.

Если перед вами все элементы, вы их знаете, или даже видите — например, собрали все это в одном месте — то перед вами не система, а набор элементов. Просто куча деталей.

Как из этой кучи сделать систему? Нужно поставить элементы на свои места и включить — запустить систему в работу.

Это хорошо понимают обычные программисты, или инженеры. Вот программный код, вот компьютер или сервер, вот входные данные для обработки. Нажимаешь ВКЛ — система заработала. Ну или не заработала, если в ней есть ошибка.

В системах, состоящих из людей, обычно все наоборот, и это отличие — ключевое. Системы из людей работали до вас, и будут работать после вас. Но не будут работать _при вас_, в вашем присутствии. Собственно, в вашем присутствии они перестают быть системами, и снова превращаются в набор элементов.

Возвращаясь к примеру выше, когда вы собрали все и всех элементов системы в одном месте. Что вы сделали? Вы _выключили_ систему.

Чем отличается система во включенном и выключенном состояниях? Люди вроде те же, должности те же, процессы те же, руководитель тот же — все на месте.

Отличие в свойствах системы, которые проявляют себя только при ее «включении», т.е. когда система работает.

Примеры таких свойств систем — повсюду, вы их найдете без труда.

Телевизор без электричества — выключенная система, которая не демонстрирует нам главной своей функции — показывать изображение. Включаете телевизор — увидите изображение, функция проявится. Плеснете на работающий телевизор воды — увидите новое свойство системы, о котором, возможно, и не подозревали.

Такие свойства системы называются _эмерджентными_, или _возникающими_.

Возникают они, когда из набора элементов собирается и включается система. Важны оба условия — и собирается, и включается. В нашем случае — когда не выключается.

Итак, наша задача — понять систему, чтобы впоследствии ее изменить. Как понять систему?

#### Не выключать

Очень просто — наблюдать за ней, не выключая.

Так же, как мы отлаживаем код — включаем и смотрим, что получится. В принципе, можно код и глазами отлаживать, да в распечаточке — помните, в институте, «листинг программы»? Но так, вроде, мало кто делает. Слишком сложны системы, которые мы создаем. Очень много зависимостей, которые не то чтобы нам не подвластны, но ковыряться в них при отладке — дело неблагодарное.

С обычными, не компьютерными системами все еще сложнее. Там нет «листинга». Представьте, каким кайфом стала бы работа с «людскими» системами, будь там флажок «Pause on caught exceptions»?

Как мы обычно выключаем систему:  
1\. Разговариваем с сотрудниками по-отдельности;  
2\. Разговариваем со всеми сотрудниками сразу;  
3\. Вывозим всех на неформальное мероприятие;  
4\. Делаем запрос сотрудникам, ставим задачу, просим отчет;  
5\. Просим описать их деятельность, или написать бизнес-процесс;  
6\. Собираем руководителей на совещание;  
7\. Спрашиваем у бывших сотрудников, как работает система;  
8\. И т.д.

Получается, все наши обычные действия приводят к выключению систем и попыткам понять эмерджентные свойства по набору элементов.

Шерлок Холмс с такой работой отлично справлялся, он называл это дедукцией — понять картину по отдельным деталям. Правда, у него другого выхода не было — не попросишь же преступника повторно совершить злодеяние в присутствии гения сыска.

У нас ситуация проще, и возможность наблюдать работающие, неизмененные системы — есть.

Лучший метод, конечно — постоянно присутствовать в системе, быть ее частью и одновременно наблюдать ее отстраненно. Это, например, путь скрам-мастера. И, по определению — роль непосредственного руководителя. Если он, конечно, не бегает по совещаниям вместо работы.

Аналогичный пример — тренер, например в футбольной команде. Там наблюдение за системой в действии, во всей ее мощи — часть работы.

Что делать нам, офисным работникам, разделенным перегородками, кабинетами, иногда континентами?

Вести скрытое наблюдение, лично или с использованием технических средств.

#### Наблюдение

Личное наблюдение не всегда возможно, тут все зависит от вашего положения относительно наблюдаемой системы.

Если вы работаете внутри организации, то можете просто разместить свое рабочее место там, где находится система — люди, взаимодействие которых вы хотите понять.

Первое время вы будете инородным, выключающим систему элементом. Но постепенно к вам привыкнут, и перестанут обращать на вас внимание.

Чтобы к вам привыкли побыстрее, делайте вид, что вам не особо интересно, что происходит вокруг. Можно делать вид, что вы увлеченно работаете за компьютером, надеть наушники и включить музыку — но негромко, чтобы слышать происходящее вокруг. Не делайте вид, что слушаете разговоры. Точнее, делайте вид, что не слушаете разговоры. Думаю, дальше вы сами придумаете, как влиться.

Если в вашей команде есть люди, которым будет проще влиться в систему, то можно отправить их, дав четкую установку.

Можно использовать разнообразные [средства отслеживания действий людей в системах](https://habr.com/ru/post/436570/). Всей системы вы таким способом не увидите, но хотя бы узнаете, пользуются люди вашими инструментами, или нет. На словах они говорят одно, а на деле — другое.

Практика показывает, что обычно достаточно 2-5 дней, чтобы составить представление о системе. Это будет не предельно точная картина, а эскиз, дающий общее, интегральное видение системы.

Эскиз впоследствии можно дополнять деталями, уже без использования наблюдения. Например, дополнить данными проверки гипотез, данными контроллинговых систем и т.д.

Что интересно — наблюдение помогает развить способности к прогнозированию. Прогнозирование помогает быстро понять, исходя из опыта и знания о поведении систем, какие методы и изменения сработают и принесут результат, а какие нет. Это еще одно применение системного мышления и эмерджентных свойств систем, об этом поговорим ниже.

В итоге, наблюдение за работающей, не выключенной системой — отличный метод, который сложно чем-то заменить. Наблюдение помогает увидеть систему максимально точно, беспристрастно и объективно, без интерпретаций.

Любой другой вариант — _интерпретация_, или проекция в определенной системе координат. Особенно если вы спрашиваете о системе у ее руководителя (как чаще всего и бывает). Это относится не только к работе программиста, но и к ежедневной рутине управления.

Собственно, ничего нового в этом подходе нет, он часто используется в определенных областях.

Например, в рознице и сфере услуг используются тайные покупатели — люди, которых целенаправленно отправляют в магазин, гостиницу и т.д., чтобы они увидели систему в действии, как она есть.

Новым в этом подходе является использование его в работе обычного предприятия, как правило не связанного с розницей — производственного, например. Берем старый известный метод, находим новое применение.

#### Прогнозирование

Теперь о прогнозировании. В работе программиста часто встречается ситуация, когда нужно дать прогноз успешности того или иного проекта. Обычно речь о проектах внутреннего организационного развития компании. Проще говоря, о проектах изменений.

Спрашивают обычно о чужих проектах — тех, в которых не участвует бизнес-программист. Т.е. о проектах, выполняемых не по правилам бизнес-программирования, а по правилу «как умею».

Бизнес-программист, после краткого изучения информации о планируемом проекте, обычно говорит — ничего полезного не получится. Или — ничего не получится вообще. Разница понятна — проект может быть выполнен успешно, в сроки и бюджеты, но не принесет никакой пользы компании.

Высказанное мнение, т.е. прогноз бизнес-программиста, обычно вызывает негативные реакции — депрессию, гнев, отторжение, «да кто ты такой?», «и.о. Бога на Земле, что ли?» и т.д.

Негативная реакция усиливается, когда прогноз сбывается, а сбывается он очень часто.

Однако, не все так печально, и постепенно люди начинают привыкать к такой «сверхспособности» бизнес-программиста, и даже адекватно ей пользоваться для блага компании, или своего личного. Некоторые даже учет прогнозов ведут — тетрадь, в которой отмечают галочкой «он был прав». Например, такая тетрадь была у двоих моих коллег-руководителей. Не знаю, правда, виртуальная или настоящая.

Теперь разберемся, как бизнес-программист делает такие прогнозы.

#### Откуда берутся прогнозы

Все дело в использовании знаний о поведении систем.

Проект изменений всегда содержит в себе минимум две системы: изменяемая и изменяющая.

Изменяемая — _что мы собираемся улучшить_. Бизнес-процесс, работа подразделения, взаимодействие функций и т.д. Будем называть ее _объект изменений_.

Изменяющая — _тот, кто придумывает, реализует и имплементирует изменения_. Проще говоря — команда внедрения изменений. Будем называть ее _субъект изменений_.

Обе системы состоят из набора элементов и связей между ними. Это люди, информационные системы, цели, формальные и неформальные отношения, модель управления, подходы руководства, влияющие силы и т.д.

В субъекте, т.е. проекте и команде изменений, есть специфические элементы — алгоритм выбора внедряемых методов, цель и мотивация руководителя проекта и команды, методика внедрения, принципы управления проектом, подходы руководства к оценке хода и результатов проекта, планы команды на жизнь после проекта, выбор решаемой проблемы и т.д.

Достоверно увидеть все элементы и связи не может никто, даже самый матерый бизнес-программист. Но какую-то, определенную часть видят все — и руководитель проекта внедрения, и руководитель компании, и все окружающие коллеги.

Однако, самый точный прогноз дает именно бизнес-программист. Все смотрят на одно и то же. Видят объект, видят субъект, план проекта, ресурсы, окружающую среду. Но прогноз кардинально различается. Почему?

Ответ очень прост, и даже скучен: бизнес-программист учитывает _историческую информацию_. Историческую и статистическую информацию о поведении схожих систем.

Результат проекта внедрения изменений складывается из _сочетания_ двух систем — объекта и субъекта. Если системы сочетаются неправильно, результат будет отрицательным.

Если затевается новый проект изменений, но системы объекта и субъекта практически не изменились, результат с высокой вероятностью будет аналогичным. Те же люди, пытаются внедрить тот же метод в том же подразделении.

Примеров масса. Если посмотрите системным взглядом на историю внедрения изменений вашей компании, увидите подтверждение этой закономерности.

Можно и на улице примеры поискать, сейчас как раз подходящая система — «зима» называется. Зима \+ город \+ эти, как их, которые снег должны убирать. Годы идут, а результат аналогичный. Потому что все системы на месте, без изменений. Ах, да, иногда зима бывает без снега — тогда и результат весьма неплох. Только чей он?

Самое сложное в таком подходе — определить, _есть отличия_ в системах или нет. Чтобы сделать это, нужно научиться ранжировать элементы и связи системы по важности — выделять ее ключевые, системообразующие элементы и связи.

Единого рецепта здесь нет, вариантов много. Есть, например, метод 7S, созданный в компании McKinsey, который разбирает систему на 7 частей. Лично я предпочитаю себя не ограничивать, иначе можно просмотреть что-то новое для себя.

Понимание ключевых элементов можно делать интуитивно, но надо себя перепроверять, т.к. качество интуиции зависит от текущего уровня вашего развития как бизнес-программиста, и может вас обмануть.

Выделение ключевых элементов позволит делать прогноз быстрее, не погружаясь в детали и не изучая шум. Вы просто видите, что ключевые элементы обеих систем остались на месте, и можете быть уверены — с высокой вероятностью результат повторится.

Чем чаще вы будете делать такое упражнение, тем быстрее разовьются навыки, и тем точнее станут ваши прогнозы.

Есть такое крылатое выражение в нашей стране — «хотели как лучше, а получилось как всегда». Теперь, после прочитанного, вы понимаете, что здесь чего-то не хватает. Правильнее будет «хотели как лучше, действовали как всегда, ну вот и результат...».

Видел пример такого подхода у нашего министра иностранных дел, Сергея Лаврова. На пресс-конференции после встречи с госсекретарем США Рексом Тиллерсоном Лавров сказал: «Что касается конкретно проблемы Сирии, в частности Б.Асада, то сегодня мы обсуждали исторические экскурсы, и Р. Тиллерсон сказал, что он человек новый и предпочитает не копаться в истории, а заниматься сегодняшними проблемами. Однако мир устроен так, что если мы не извлекаем уроки из прошлого, то едва ли сможем преуспеть в настоящем».

Дальше Лавров перечислил несколько примеров — сочетаний систем объекта и субъекта, с одинаковой целью субъекта — внедрение модели демократии через свержение диктатора. НАТО и Ирак, НАТО и Ливия. И спрогнозировал результат сочетания систем НАТО и Сирия.

Пока, вроде, прав Лавров.