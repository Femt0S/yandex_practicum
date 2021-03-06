# [![viewJupyter](https://img.shields.io/badge/Jupyter-view-orange?style=for-the-badge&logo=Jupyter)](01_preprocessing.ipynb) Исследование надёжности заёмщиков 

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/)


## Описание проекта

Исходный набор данных и поставленная задача представлена кредитным отделом банка "N". Необходимо разобраться о влиянии различных признаков на факт погашения кредита в срок.

## Описание данных
- `children` — количество детей в семье
- `days_employed` — общий трудовой стаж в днях
- `dob_years` — возраст клиента в годах
- `education` — уровень образования клиента
- `education_id` — идентификатор уровня образования
- `family_status` — семейное положение
- `family_status_id` — идентификатор семейного положения
- `gender` — пол клиента
- `income_type` — тип занятости
- `debt` — имел ли задолженность по возврату кредитов
- `total_income` — ежемесячный доход
- `purpose` — цель получения кредита

## Поставленные задачи

- **Предобработка данных**:
  - определить и заполнить пропущенные значения;
  - привести типы данных в соответствие;
  - удалить дубликаты:
    - выбрать подходящий метод для поиска и удаления дубликатов;
    - применить его;
    - определить возможные причины появления дубликатов;
  - выделить леммы в значениях столбца с целями получения кредита;
  - категоризовать данные;

- **Основные вопросы**
  - Есть ли зависимость между возвратом кредита в срок и:
    - наличием детей;
    - семейным положением;
    - уровнем дохода;
  - Как разные цели кредита влияют на его возврат в срок?
