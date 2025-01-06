# MULTIMEDIA

Журкин Александр группа М8О-410Б-21

ЛР №1 Проведение исследований с алгоритмом KNN

ЛР №2 Проведение исследований с логистической и линейной регрессией.

ЛР №3 Проведение исследований с решающим деревом.

ЛР №4 Проведение исследований со случайным лесом.

ЛР №5 Проведение исследований с градиентным бустингом.

# Вывод:
Можно сделать вывод, что наилучшее качество по выбранным метрикам для классификации показала модель градиентного бустинга из sklearn (accuracy 0.9972), а для регрессии - улучшенная модель KNN из sklearn (R^2 0.9588).

# Результаты лабораторных работ

Классификация - Бейзлайн (метрика accuracy) - Улучшенный бейзлайн (метрика accuracy)
Регрессия - Бейзлайн (метрика R^2) - Улучшенный бейзлайн (метрика R^2)

Модель|Задача|Бейзлайн|Улучшенный бейзлайн|
|---|---|---|---|
|KNN |Классификация |0.95125 | 0.95525 |
|Мой KNN | |0.6  |0.6  |
|KNN |Регрессия |0.4045 | 0.9588|
|Мой KNN | |0.8420   |0.8636 |
|Логистическая регрессия |Классификация |0.994   | 0.9842     |
|Моя логистическая регрессия | |0.9272   |  0.9395      |
|Логистическая регрессия |Регрессия | 0.7398  | 0.823      |
|Моя логистическая регрессия | | 0.7398  | 0.634   |
|Решающее дерево |Классификация | 0.987   | 0.9877   |
|Моё решающее дерево | | 0.985  | 0.985   |
|Решающее дерево |Регрессия | 0.937  |  0.9335     |
|Моё решающее дерево | |0.9341   |  0.9341  |
|Случайный лес |Классификация |0.9895   |0.9887    |
|Мой случайный лес | | 0.77  |0.84    |
|Случайный лес |Регрессия | 0.9513  | 0.9493   |
|Мой случайный лес | |0.6068   | 0.5552   |
|Градиентный бустинг |Классификация | 0.9972  | 0.9825   |
|Мой градиентный бустинг | |0.975   | 0.9916   |
|Градиентный бустинг |Регрессия | 0.8772  | 0.8642   |
|Мой градиентный бустинг | | 0.7339  | 0.8642   |



# Датасеты
Для классификации - датасет 'Loan new dataset' https://www.kaggle.com/datasets/willianoliveiragibin/financial-risk-v2,
Задача: определять, разрешат ли кредит клиенту(столбец LoanApproved (0 - не разрешено, 1 - разрешено)) \
Для регрессии - датасет 'medical_insurance' https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction,
Задача: предсказывать цену страховки(столбец charges).
