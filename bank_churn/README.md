# Описание проекта "[Отток клиентов банка](bank_churn.ipynb)"

## Задача

Необходимо спрогнозировать, уйдет клиент из банка в ближайшее время или нет.

## Данные

Информация о клиентах банка, в том числе факт их ухода.

Источник данных: https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling


## Библиотеки

*pandas, sklearn, catboost, lightgbm, matplotlib, seaborn*

## Вывод

Удалось достичь качества лучшей модели (CatBoost) с учетом дисбаланса классов F1=0.62, AUC-ROC=0.86.
