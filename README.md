#
|                                                                      **Название проекта**                                                                      |                                                                                                                                                                                                                                                                   **Описание**                                                                                                                                                                                                                                                                  |            **Используемые библиотеки**           |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------:|
| [Исследование надёжности заёмщиков — анализ банковских данных](https://github.com/Fedotov143/Projects/tree/main/Credit)                                   | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующиехранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца икатегоризированны данные                                                                                                                                                                                             | pandas                                |
| [Продажа квартир — анализ рынка недвижимости](https://github.com/Fedotov143/Projects/tree/main/Real%20estate)                                  | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, параметры квартир, в зависимости от удаленности от центра. Проведена преодобработка даных. Построены гистограммы, боксплоты, диаграммы рассеивания                                                                                                                                                                                                                                                                               | pandas, matplotlib                               |
| [Определение выгодного тарифа для телеком компании](https://github.com/Fedotov143/Projects/tree/main/Teriff%20plan)                                               | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.                                                                                                                                                                | pandas, numpy, scipy, matplotlib, seaborn, functools           |
| [Изучение закономерностей, определяющих успешность игр](https://github.com/Fedotov143/Projects/tree/main/Games%20industry)                                        | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. | pandas, numpy, scipy, matplotlib, seaborn, plotly |
| [Исследование данных авиакомпании — проверить гипотезу о повышении спроса во время фестивалей](https://github.com/Fedotov143/Projects/tree/main/Flights)        | Проверена гипотеза о различии среднего спроса на билеты во время проведения различных фестивалей                                                                                                                                                                                                                                                                                                                                                                                                                                                | pandas, numpy, matplotlib, seaborn |
| [Оптимизация маркетинговых затрат в Яндекс.Афише](https://github.com/Fedotov143/Projects/tree/main/Afisha%20marketing)                                    | Проведен анализ данных от Яндекс.Афиши целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI                                                                                                                                                                                                                                                                                                                                                                                                 | pandas, numpy, seaborn, matplotlib, plotly               |
| [Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста](https://github.com/Fedotov143/Projects/tree/main/A%3BB%20test)          | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.                                                                                                                                                  | pandas, numpy, scipy, matplotlib, datetime, seaborn, plotly, collections|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](https://github.com/Fedotov143/Projects/tree/main/Food%20industry) | Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly. Также мне потребовалось получить район расположения кафе-конкурентов. Эту задачу я решил, найдя данные в интернете                                                                                                          | pandas, numpy, seaborn, matplotlib, plotly              |
| [Анализ пользовательского поведения в мобильном приложении](https://github.com/Fedotov143/Projects/tree/main/Mobile%20app)                                        | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.                                                                                                                                        | pandas, numpy, scipy, matplotlib, seaborn, math, pylab, plotly |
| [Анализ пользовательского взаимодействия с карточками Дзен](https://github.com/Fedotov143/Projects/tree/main/Dzen)                                        | В проекте подразумевается создание дэшборда для менеджеров, чтобы автоматизировать процесс отслеживания взаимодействия пользователей с карточками Яндекс.Дзена.Нужно было подключиться к виртуальной машине, через Яндекс.облако, после создать базу данных с помощью терминала, далее создать дата-пайплайн и после загрузить код дашборда. Работа выполняется на основе предоставленного технического задания | postgresql, SQL, sqlalchemy, Яндекс.Облако, dash, sys, getopt, plotly, pandas |
| [Прогнозирование вероятности оттока пользователей для фитнес-центров](https://github.com/Fedotov143/Projects/tree/main/Fitness)                            | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. | pandas, numpy, matplotlib, seaborn, Scikit-learn |
| [Выпускной проект:](https://github.com/Fedotov143/Projects/tree/main/Final%20project) 
| | 1. Определение неэффективных операторов телеком-компании «Нупозвони» | Определить самых неэффективных операторов по определенным признакам низкой эффективности | Python, Pandas, Matplotlib, предобработка данных, исследовательский анализ данных, визуализация данных, проверка статистических гипотез, построение дашбордов и презентации |
| | 2. Оценка результатов A-B-теста | По данным действий пользователей необходимо оценить корректность проведения A/B теста и проанализировать результаты | Python, Pandas, Matplotlib, SciPy, A/B-тестирование, проверка статистических гипотез |
| | 3. Книжное дело | Компанией было приобретен крупный сервис для чтения книг по подписке. Необходимо проанализировать имеющуюся информацию и определить направления развития | SQL, Python |
