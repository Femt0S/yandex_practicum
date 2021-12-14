# [![viewJupyter](https://img.shields.io/badge/Jupyter-view-orange?style=for-the-badge&logo=Jupyter)](11_time_series.ipynb) Прогнозирование заказов такси

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.19-cyan.svg)](https://numpy.org/) [![scikit-learn](https://img.shields.io/badge/sklearn-0.24-orange.svg)](https://scikit-learn.org/) [![LightGBM](https://img.shields.io/badge/LightGBM-3.2.1-red.svg)](https://lightgbm.readthedocs.io) [![CatBoost](https://img.shields.io/badge/CatBoost-1.0-yellow.svg)](https://catboost.ai/) [![Matplotlib](https://img.shields.io/badge/matplotlib-3.4-white.svg)](https://matplotlib.org/) [![Seaborn](https://img.shields.io/badge/seaborn-0.11-green.svg)](https://seaborn.pydata.org/) ![datetime](https://img.shields.io/badge/datetime-_-gray.svg) ![statsmodels](https://img.shields.io/badge/statsmodels-_-gray.svg)

## Описание проекта

Предоставлены исторические данные о заказах такси в аэропортах. Необходимо спрогнозировать количество заказов такси на следующий час методами машинного обучения.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.

## Описание данных

Индексом является время получения данных (timestamp)

Количество заказов находится в столбце `num_orders` (от англ. number of orders, «число заказов»).
    
## Поставленные задачи

- Загрузить и проанализровать данные;
- Произвести ресемплирование данных с шагом в 1 час;
- Обучить модели с разными гиперпараметрами;
- Проверить результат работы моделей на тестовой выборке, выбрать оптимальный вариант.
