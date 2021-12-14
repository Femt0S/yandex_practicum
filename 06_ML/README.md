# [![viewJupyter](https://img.shields.io/badge/Jupyter-view-orange?style=for-the-badge&logo=Jupyter)](06_ML.ipynb) Отток клиентов 

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.19-cyan.svg)](https://numpy.org/) [![scikit-learn](https://img.shields.io/badge/sklearn-0.24-orange.svg)](https://scikit-learn.org/) [![Matplotlib](https://img.shields.io/badge/matplotlib-3.4-white.svg)](https://matplotlib.org/) [![Seaborn](https://img.shields.io/badge/seaborn-0.11-green.svg)](https://seaborn.pydata.org/)

## Описание проекта

Из условного «Бета-Банка» начали уходить клиенты. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Необходимо подготовить модель машинного обучения с максимальным значением F1-меры (>0.59).

## Описание данных

**Признаки**

- `RowNumber` — индекс строки в данных
- `CustomerId` — уникальный идентификатор клиента
- `Surname` — фамилия
- `CreditScore` — кредитный рейтинг
- `Geography` — страна проживания
- `Gender` — пол
- `Age` — возраст
- `Tenure` — сколько лет человек является клиентом банка
- `Balance` — баланс на счёте
- `NumOfProducts` — количество продуктов банка, используемых клиентом
- `HasCrCard` — наличие кредитной карты
- `IsActiveMember` — активность клиента
- `EstimatedSalary` — предполагаемая зарплата

**Целевой признак**

- `Exited` — факт ухода клиента

## Поставленные задачи

- Загрузить и подготовить данные;
- Исследовать баланс классов, обучить модель без учёта дисбаланса;
- Улучшить качество модели, учитывая дисбаланс классов. Обучить разные модели и найти лучшую;
- Финальное тестирование лучшей модели.
