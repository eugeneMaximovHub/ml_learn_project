# Портфолио проектов
В репозитории содержатся проект курса Open Machine Learning course [open data science](https://ods.ai/).


## Проекты с курса "Open Machine Learning course"
| № | Проект    | Задачи проекта   | Описание проекта                                                   | Навыки и инструменты  |
|---|-----------|------------------|--------------------------------------------------------------------|-----------------------|
|1|[Предварительный анализ данных с помощью Pandas](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment01_exploratory_data_analysis_with_pandas)|Изучить библиотеку Pandas и провести первичный анализ данных.|В ходе выполнения были изучены и применены некоторые функции Pandas.|Pandas, Numpy, Python, Обработка данных,|
|2|[Анализ данных о сердечно-сосудистых заболеваниях](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment02_analyzing_cardiovascular_disease_data)|Спрогнозировать наличие или отсутствие сердечно-сосудистых заболеваний (ССЗ), используя результаты обследования пациента.|Используя данные опроса пациентов и результаты обследования, провели визуальный анализ данных, предварительно их очистив. Построена корреляционная матрица. Проанализированы зависимости риска ССЗ от некоторых параметров.|Корреляционная матрица, Pandas, Numpy, seaborn, matplotlib|
|3|[Деревья решений с набором данных UCI](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment03_decision_trees_with_a_toy_task_and_the_UCI_adult_dataset)|Изучить как работают деревья решений. Решить задачу бинарной классификации, определить по демографическим данным уровень дохода.|В ходе проекта изучен принцип работы деревьев решений. Проведена очистка и подготовка данных. Для набора демографических данных составлены модели предсказания уровня дохода, используя дерево решений и случайный лес без настройки и с настройкой параметров.|sklearn, энтропия, дерево решений, случайный лес, предобработка данных|
|4|[Исследование OLS, Лассо и случайного леса в задаче регрессии](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment04_exploring_OLS_lasso_and_random_forest_in_a_regression_task)|Используя набор данных с параметрами вина, проанализировать зависимость его качества от различных параметров, составить модель предсказания категории качества.|Проведено разделение данных на тренировочный и тестовый набор. Обучены модели линейной регрессии, регрессии лассо и случайного леса. Составлена таблица ранжирования значимости параметров.|разделение набора на выборки, линейная регрессия, регрессия лассо, случайный лес, ранжирование|
|5|[Логистическая регрессия и случайный лес в задаче кредитного скоринга](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment05_logistic_regression_and_random_forest_in_the_credit_scoring_problem)|Спрогнозировать, погасит ли клиент свой кредит в течение 90 дней.|Проведена подготовка и нормализация данных о клиентах. Построены модели логистической регрессии, случайного леса и bagging-а. Найдены значимости функций для целевой переменной. Проведено сравнение разных моделей.|регрессия, случайный лес, bagging, нормализация, оценка ROC AUC, ранжирование|
|6|[Идентификация пользователя в сети Интернет](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment06_identification_of_a_user_on_the_Internet)|Для каждой сессии нужно предсказать, принадлежит ли сессия Alice (метка «1»), или нет (метка «0»). Целевая метрика – ROC AUC. Конкурс [kagle](https://www.kaggle.com/c/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2)|Проведена подготовка данных. Изменено разделение данных. Преобразуем данные с помощью CountVectorizer. Обучена логистической регрессии.|CountVectorizer, логистическая регрессия|
|7|[Обучение без учителя](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment07_unsupervised_learning)|Провести кластеризацию набора данных и классифицировать кластеры.|Используется набор данных об активности пользователей на основе данных [Samsung Human Activity Recognition](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) Провели масштабирование выборки с использованием StandardScaler параметров по умолчанию. Сократили количество измерений. Найдено минимальное количество основных компонентов, необходимых для покрытия 90% дисперсии исходных (масштабированных) данных. Выполнена кластеризация для не размеченного набора данных. Применён алгоритм агломеративной кластеризации|кластеризация, агломеративная кластеризация, Метод главных компонент, перекрёсная проверка|
|8|[Линейная регрессия и стохастический градиентный спуск](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment08_implement_sgd_regressor)|Реализовать собственный класс SGDRegressor|Написали собственный класс SGDRegressor и протестировали его на наборе данных о росте / весе. Проведена оценка среднеквадратичной ошибки|LinearRegression, стахастический градиентный спуск|
|9|[Анализ временных рядов](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment09_time_series_analysis)|Используя Prophet и ARIMA провести анализ количества просмотров [страницы](https://en.wikipedia.org/wiki/Machine_learning) Википедии, посвященной машинному обучению.|Спрогнозировано количество просмотров страницы на определенную дату. Применены модели предсказания FB Prophet, ARIMA и SARIMAX. Проведен подбор параметров.|Проверка стационарности, FB Prophet, ARIMA, SARIMAX|
|10|[Градиентный бустинг](https://github.com/eugeneMaximovHub/ml_learn_project/tree/main/assignment10_flight_delays_kaggle)|Решить задачу [Kaggle Inclass competition](https://www.kaggle.com/c/flight-delays-spring-2018)|Обучена модель XGBoost для предсказания, будет ли рейс задержан более чем на 15 минут.|XGBoost|