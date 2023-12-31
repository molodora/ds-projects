# Учебные проекты по DS
В этом репозитории находятся учебные проекты, созданные в процессе изучения Data Science. Ниже представлено краткое описание каждого проекта.

|Название|Сфера деятельности|Тип задачи|Описание|Библиотеки|
|-|-|-|-|-|
[Предсказание температуры стали во время плавки](steel/)|Промышленность|Задача регрессии, создание признаков|Построение модели для определения температуры стали в зависимости от различных параметров процесса обработки|*numpy, pandas, sklearn, lightgbm, xgboost, catboost, matplotlib, seaborn*
[Прогнозирование оттока клиентов банка](bank_churn/)|Банковская сфера|Бинарная классификация с дисбалансом классов|Прогнозирование факта ухода клиентов из банка|*pandas, sklearn, catboost, lightgbm, matplotlib, seaborn*|
[Определение наиболее выгодного региона для нефтедобычи](well_location/)|Добывающие компании|Линейная регрессия, метод бутстрепа|Выбор региона для добычи нефти с наибольшей прибылью и наименьшими рисками|*numpy, pandas, sklearn, matplotlib, seaborn*|
[Прогнозирование количества заказов такси на следующий час](taxi/)|Бизнес, интернет-сервисы|Регрессия на временных рядах|Создание модели для предсказания объема заказов такси|*pandas, sklearn, catboost, lightgbm, statsmodels, matplotlib*
[Поиск токсичных комментариев](toxic_comments/)|Интернет-сервисы|Классификация текстов (**NLP**), дисбаланс классов|Оценка тональности комментария|*numpy, pandas, sklearn, torch, lightgbm, catboost*
[Определение возраста покупателей по фотографии](customers_age/)|Бизнес|Регрессия на изображениях (**CV**)|Определение возраста человека по фотографии|*pandas, keras, seaborn*