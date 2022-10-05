# yandex_practicum
Учебные проекты Яндекс.Практикум 


|  Название проекта | Сферы деятельности |   Инструментарий  |   Задачи проекта   |  Описание проекта | Ключевые слова проекта | 
| -------------     | -------------      | -------------     | -------------      | -------------     |     -------------      |
| 1. Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов | Интернет-сервисы, Стриминговый сервис|Pandas, Python| На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга. | Сравнение Москвы и Петербурга окружено мифами: - Москва — мегаполис, подчинённый жёсткому ритму рабочей недели; - Петербург — город своеобразной культуры, непохожий на Москву. Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки вы проверите данные и сравните поведение пользователей двух столиц. | обработка данных, дубликаты, пропуски, логическая индексация, группировка, сортировка |
| 2. Исследование надёжности заёмщиков — анализ банковских данных | Банковская сфера, Кредитование | Pandas, Python, предобработка данных | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовано влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. | обработка данных, дубликаты, пропуски, категоризация, декомпозиция |
| 3. Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости | Интернет-сервисы, Площадки объявлений | Python, Pandas, Matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | обработка данных, histogram, boxplot, scattermatrix, категоризация, scatterplot,  фрод-мониторинг |
| 4. Определение выгодного тарифа для телеком компании | Телеком | Matplotlib, NumPy, Pandas, Python, SciPy, описательная статистика, проверка статистических гипотез | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента |
| 5. Изучение закономерностей, определяющих успешность игр | Gamedev, Интернет-магазины | Python, Pandas, NumPy, Matplotlib, предобработка данных, исследовательский анализ данных, описательная статистика, проверка статистических гипотез | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. | обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента, piechart |
| 6. Анализ убытков приложения ProcrastinatePRO+ | Интернет-сервисы, Стартапы | Python, Pandas, Matplotlib, когортный анализ, юнит-экономика, продуктовые метрики, Seaborn | Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс. | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным. | обработка данных, статистический тест, LTV, CAC, когортный анализ |
| 7. Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста | Интернет-магазины | Python, Pandas, Matplotlib, SciPy, A/B, тестирование | Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Проведен анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам и посчитана статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста проверка статистических гипотез. | A/B-тест, статистический тест, фреймворк, RICE, ICE |
| 8. Исследования рынка общепита в Москве для принятия решения об открытии нового заведения | Стартапы, Бизнес, Оффлайн | Python, Pandas, Seaborn, Plotly, визуализация данных | Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов | Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовала библиотеки seaborn и plotly. | обработка данных, визуализация данных, создание презентаций |
| 9. Анализ пользовательского поведения в мобильном приложении | Стартапы, Бизнес, Интернет-сервисы | A/B-тестирование, Python, Pandas, Matplotlib, Seaborn, событийная аналитика, продуктовые метрики, Plotly, проверка статистических гипотез, визуализация данных | На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования | В данном проекте мной были изучены принципы событийной аналитики. Я построилa воронку продаж, исследовалa путь пользователей до покупки. Проанализировалa результаты A/B-теста введения новых шрифтов. Сравнилa 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнилa с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | A/B-тест, визуализация, статистический тест |
| 10. Прогнозирование вероятности оттока пользователей для фитнес-центров | Бизнес, Оффлайн | Python, Pandas, Scikit-learn, Matplotlib, Seaborn, машинное обучение, классификация, кластеризация | На основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. | KMeans, Machine Learning, дендрограмма, RandomForestClassifier, LogisticRegression |
| 11. Выпускной проект | Gamedev | A/B-тестирование, Python, Pandas, Matplotlib, Seaborn, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных | Исследование и выявление зависимости поведения пользователей игры от каналов привлечения. | Проведен анализ поведения игроков в зависимости от источника перехода. - Проведен исследовательский анализ данных; - Проанализировано влияние источника перехода в игру на поведение пользователя; - Проверены статистические гипотезы | обработка данных, A/B-тест, визуализация, статистический тест |
| 12. Выпускной проект | Интернет-магазины | SQL, PostgreSQL | Анализ базы данных с помощью SQL | Проведен анализ базы данных книг с помощью SQL | обработка данных, выгрузка данных, SQL |
| 13. Выпускной проект | Интернет-сервисы, интернет-магазины | A/B-тестирование, Matplotlib, Pandas, Python, Seaborn, визуализация данных, проверка статистических гипотез | Оценка результатов А/В теста, связанного с внедрением улучшенной рекомендательной системы | Изучены результаты тестирования изменений, связанные с внедрением улучшенной рекомендательной системы.  Для этого мы провели: - Оценка корректности проведения теста, - Анализ результатов теста. Чтобы оценить корректность проведения теста, проверили: - пересечение тестовой аудитории с конкурирующим тестом, - совпадение теста и маркетинговых событий, другие проблемы временных границ теста. | A/B-тест, визуализация, статистический тест |
