# testcenter
Python test tasks

**selenium_simple/**\
Описание таблиц:\
В таблице usn – признаки упрощенной системы налогообложения\
В таблице dohrash – доходы и расходы компаний\
В таблице kolrab – среднее количество сотрудников\
ЗАДАНИЕ:\
Взять из таблицы dohrash топ-25 компаний по доходам\
Получить ФИО директора по ИНН компании: реализовать алгоритм на Selenium / requests / BS4\

**pandas_test/**\
Необходимо эффективно получить вложенный нормализированный (пример в скриншоте) массив данных из колонки «product.products» в dataframe.\
Один продукт - одна строка.\
Итоговый dataframe должен содержать колонку с ключем исходной строки _regNum и внутренний ключ inner_index (от 1 по возрастанию).\
Пример итогового DataFrame в виде скриншота прилагается.\
df.shape = (134480, 48)
