# Описание проекта
В целях предотвращения ухода текущих клиентов банка нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. 
Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
# Задачи проекта
- проведение разведочного анализа данных (EDA),
- исследование баланса классов,
- подготовка несколько моделей машинного обучения (обучались LogisticRegression и RandomForest),
- определение оптимальной модели машинного обучения, способной предсказать уход клиента из банка в ближайшее время
- проведение финального тестирования
# Используемые библиотеки
- pandas
- seaborn
- matplotlib
- sklearn
# Данные (предоставлены Яндекс.Практикум)
Таблица Churn:
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата
- Exited — факт ухода клиента (Целевой признак)
