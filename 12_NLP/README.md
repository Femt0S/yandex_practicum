# Проект для «Викишоп»

[![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) ![re](https://img.shields.io/badge/re-_-gray.svg) [![NLTK](https://img.shields.io/badge/NLTK-3.6-gray.svg)](https://www.nltk.org/) [![scikit-learn](https://img.shields.io/badge/sklearn-0.24-orange.svg)](https://scikit-learn.org/) [![PyTorch](https://img.shields.io/badge/PyTorch-1.9-orange.svg)](https://pytorch.org/) [![transformers](https://img.shields.io/badge/transformers-BERT-yellow.svg)](https://huggingface.co/docs/transformers/index)

## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.
Постройте модель со значением метрики качества F1 не меньше 0.75. 

## Описание данных

- `text` — содержит текст комментария
- `toxic` — целевой признак.
    
## Поставленные задачи

- Загрузить и подготовить данные;
- Обучите разные модели;
- Проанализировать результаты.
