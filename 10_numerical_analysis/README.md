# Определение стоимости автомобилей

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.19-cyan.svg)](https://numpy.org/) [![scikit-learn](https://img.shields.io/badge/sklearn-0.24-orange.svg)](https://scikit-learn.org/) [![LightGBM](https://img.shields.io/badge/LightGBM-3.2.1-red.svg)](https://lightgbm.readthedocs.io) [![CatBoost](https://img.shields.io/badge/CatBoost-1.0-yellow.svg)](https://catboost.ai/) [![Matplotlib](https://img.shields.io/badge/matplotlib-3.4-white.svg)](https://matplotlib.org/) [![Seaborn](https://img.shields.io/badge/seaborn-0.11-green.svg)](https://seaborn.pydata.org/) ![datetime](https://img.shields.io/badge/datetime-_-gray.svg)

## Описание проекта

Необходимо построить модель для определения рычной стоимости б/у автомобиля. Предоставлены исторические данные о технических характеристиках, комплектации и ценах автомобилей. Полученная модель должна быть как точной, так и требующей минимального времени на обучение и предсказание.

    
## Описание данных

Признаки

- `DateCrawled` — дата скачивания анкеты из базы
- `VehicleType` — тип автомобильного кузова
- `RegistrationYear` — год регистрации автомобиля
- `Gearbox` — тип коробки передач
- `Power` — мощность (л. с.)
- `Model` — модель автомобиля
- `Kilometer` — пробег (км)
- `RegistrationMonth` — месяц регистрации автомобиля
- `FuelType` — тип топлива
- `Brand` — марка автомобиля
- `NotRepaired` — была машина в ремонте или нет
- `DateCreated` — дата создания анкеты
- `NumberOfPictures` — количество фотографий автомобиля
- `PostalCode` — почтовый индекс владельца анкеты (пользователя)
- `LastSeen` — дата последней активности пользователя

Целевой признак

- `Price` — цена (евро)

## Поставленные задачи

- Загрузить и подготовить данные;
- Обучить разные модели машинного обучения с подбором оптимальных гиперпараметров;
- Проанализировать скорость работы и качество моделей для выбора наилучшей.
