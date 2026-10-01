# Data Science Portfolio

Учебные проекты по машинному обучению и анализу данных.

## Проекты

| Проект | Описание | Стек |
|---|---|---|
| [nyc_taxi_duration](./nyc_taxi_duration) | Предсказание длительности поездок такси в Нью-Йорке: регрессия на геоданных, OSRM, погоде. RMSLE = 0.39 | Python, pandas, sklearn, XGBoost, LightGBM, OSRM |
| [project_1_ml](./project_1_ml) | Классификация клиентов банка: прогноз открытия депозита. Random Forest, Accuracy = 0.848 | Python, pandas, sklearn |
| [project_2](./project_2) | Анализ вакансий HeadHunter через SQL: 49 197 вакансий, 23 501 работодатель | PostgreSQL, pandas, psycopg2, plotly |

## О проекте NYC Taxi Trip Duration

**Задача:** предсказать длительность поездки такси в Нью-Йорке
по временным, географическим и погодным признакам.

**Что сделано:** объединены 4 источника (train, погода, праздники, OSRM API);
построены гео-признаки (Haversine, направление, KMeans-кластеры);
удалены выбросы (>24 ч и «телепортации» >300 км/ч);
сравнены 8 моделей регрессии; лучшая — Gradient Boosting, RMSLE 0.39.

**Стек:** Python, pandas, numpy, sklearn, XGBoost, LightGBM, OSRM API.

## Стек репозитория

Python 3, Jupyter Notebook, pandas, numpy, scipy, matplotlib, seaborn,
plotly, scikit-learn, XGBoost, LightGBM, PostgreSQL, psycopg2.

## Автор

Ivan — [@ivan299785](https://github.com/ivan299785)
