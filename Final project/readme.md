# Проект 1: Определение неэффективных операторов телеком-компании «Нупозвони»
## Описание
Необходимо определить самых неэффективных операторов по определенным признакам низкой эффективности

## Используемые инструменты и методы
изучение общей информации о данных: head(), info(), describe()
замена типов данных: to_datetime()
обработка дубликатов: duplicated(), drop_duplicates
обработка пропущенных значений: isna(), dropna()
анализ данных: groupby(), sort_values(), value_counts(), corr(), median(), merge()
построение графиков: hist(), boxplot(), plot(), heatmap(), scatter(), plot.bar(), px.bar(),
проверка статистической значимости: scipy.stats.kruskal(), scipy.stats.ttest_ind()
## Краткий вывод
Количество неэффективных операторов разнятся по всем 3 признакам:

Большое количество пропущенных входящих вызовов – 29 неэффективных операторов в 19 колл-центрах, что составляет 2% операторов от общего количества
Долгое ожидание ответа на внешний входящий звонок - 248 неэффективных оператора в 123 колл-центре, что составляет 22% операторов от общего количества
Малое количество исходящих вызовов - 269 неэффективный оператор в 98 колл-центрах, что составляет 24% операторов от общего количества


# Проект 2: Оценка результатов A-B-теста
## Описание
По данным действий пользователей необходимо оценить корректность проведения A/B теста и проанализировать результаты

## Используемые инструменты и методы
изучение общей информации о данных: head(), info(), describe()
замена типов данных: to_datetime()
обработка дубликатов: duplicated()
обработка пропущенных значений: isna(), fillna()
анализ данных: groupby(), sort_values(), merge(), query(), concat(), np.percentile(),
построение графиков: scatter(), plot(), go.Funnel()
проверка статистической значимости: z_value
## Краткий вывод
Cтоит учитывать результаты данного A/B теста при принятии решений. Улучшенная рекомендательная система повлияла на снижение активности пользователей после момента регистрации.

# Проект 3: Книжное дело
## Описание
Компанией было приобретен крупный сервис для чтения книг по подписке. Необходимо проанализировать имеющуюся информацию и определить направления развития

## Используемые инструменты и методы
подключение к БД: create_engine()
чтение запросов SQL: pd.io.sql.read_sql()
SQL: SELECT, WHERE, LIMIT, WITH, JOIN, GROUP BY, ORDER BY, HAVING, rank()
## Краткий вывод
В ходе анализа базы данных, содержащей информацию о книгах (в том числе об авторах, издательствах, оценках и обзорах), были определены следующие факты:

в базе данных хранится информация о 1000 книг
819 книг из 1000 были изданы в 21 веке (после 1 января 2000)
максимальная оценка книги является 5, а минимальная (из имеющихся) 1.5
42 книги выпустило издательство Penguin Books, что является наибольшим значением среди всех издательств (брошюры не учитывались)
автором с самыми высокими оценками (в разрезе книг автора или всех книг из БД) является Diana Gabaldon
пользователи, оставляющие более 50 оценок к книгам, в среднем делают по 24 обзора
