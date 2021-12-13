# Финальный проект на тему «Промышленность»

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.19-cyan.svg)](https://numpy.org/) [![scikit-learn](https://img.shields.io/badge/sklearn-0.24-orange.svg)](https://scikit-learn.org/) [![LightGBM](https://img.shields.io/badge/LightGBM-3.2.1-red.svg)](https://lightgbm.readthedocs.io) [![CatBoost](https://img.shields.io/badge/CatBoost-1.0-yellow.svg)](https://catboost.ai/) [![Matplotlib](https://img.shields.io/badge/matplotlib-3.4-white.svg)](https://matplotlib.org/) [![Seaborn](https://img.shields.io/badge/seaborn-0.11-green.svg)](https://seaborn.pydata.org/) ![datetime](https://img.shields.io/badge/datetime-gray.svg)

## Описание проекта

Чтобы оптимизировать производственные расходы, металлургическому комбинату требуется построение модели для снижение потребления электроэнергии на этапе обработки стали.

## Описание данных

Данные состоят из файлов, полученных из разных источников:

- `data_arc.csv` — данные об электродах;
- `data_bulk.csv` — данные о подаче сыпучих материалов (объём);
- `data_bulk_time.csv` — данные о подаче сыпучих материалов (время);
- `data_gas.csv` — данные о продувке сплава газом;
- `data_temp.csv` — результаты измерения температуры;
- `data_wire.csv` — данные о проволочных материалах (объём);
- `data_wire_time.csv` — данные о проволочных материалах (время).

Во всех файлах столбец `key` содержит номер партии.
