# [![viewJupyter](https://img.shields.io/badge/Jupyter-view-orange?style=for-the-badge&logo=Jupyter)](13_SQL.ipynb) Спрос на рейсы авиакомпании 

[![SQL](https://img.shields.io/badge/SQL-336791.svg)](https://www.postgresql.org/) [![Pandas](https://img.shields.io/badge/Pandas-1.2-blue.svg)](https://pandas.pydata.org/) [![Matplotlib](https://img.shields.io/badge/matplotlib-3.4-white.svg)](https://matplotlib.org/)

## Описание проекта
Необходимо изучить базу данных, и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие фестивали.

## Описание данных
База данных об авиаперевозках состоит из нескольких таблиц.

Таблица **airports** — информация об аэропортах:

    airport_code — трёхбуквенный код аэропорта,
    airport_name — название аэропорта,
    city — город,
    timezone — временная зона.

Таблица **aircrafts** — информация о самолётах:

    aircraft_code — код модели самолёта,
    model — модель самолёта,
    range — дальность полёта.

Таблица **tickets** — информация о билетах:

    ticket_no — уникальный номер билета,
    passenger_id — персональный идентификатор пассажира,
    passenger_name — имя и фамилия пассажира.

Таблица **flights** — информация о рейсах:

    flight_id — уникальный идентификатор рейса,
    departure_airport — аэропорт вылета,
    departure_time — дата и время вылета,
    arrival_airport — аэропорт прилёта,
    arrival_time — дата и время прилёта,
    aircraft_code — id самолёта.

Таблица **ticket_flights** — стыковая таблица «рейсы-билеты»

    ticket_no — номер билета,
    flight_id — идентификатор рейса.

Таблица **festivals** — информация о фестивалях

    festival_id — уникальный номер фестиваля,
    festival_date — дата проведения фестиваля,
    festival_city — город проведения фестиваля,
    festival_name — название фестиваля.

## Поставленные задачи:

- Проведите исследовательский анализ данных средствами SQL;
- Экспортировать данные для анализа из базы;
- Проанализировать данные средствами Python и методами статистики.
