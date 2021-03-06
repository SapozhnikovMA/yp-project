# Портфолио проектов (Учебные проекты):

# Краткое описание проектов:
1. [Оптимизация энергопотребления на этапе обработки стали](https://github.com/SapozhnikovMA/yp-project/tree/main/temp_steel):
  - По собранным данным, зафиксированных в процесса обработки стали, необходимо определить зависимости факторов и целевой признак, который необходимо предсказывать; 
  - Создание новых фичей с помощью groupby, получение нового датасета с помощью pd.merge();
  - Разведочный анализ, проверка мультиколлинеарности, создание и обучение моделей предсказания, выбор лучших моделей;
  - Определение важности признаков (features importances) и обоснование использования в моделях;
  
2.  [Отток клиентов банка](https://github.com/SapozhnikovMA/yp-project/tree/main/Bank):
  - Необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.
  - Построить модель с предельно большим значением F1-меры;
  - Модели не помогут удержать клиентов, но помогут руководству банка принять правильное решение;
  
3. [Определение возраста покупателей с помощью нейронных сетей](https://github.com/SapozhnikovMA/yp-project/tree/main/CV):
  - Подготовка фотографий;
  - Подготовка функций для обучения Resnet50;
  - Анализ моделей.

4. [Проект по определению негативных и положительных отзывов](https://github.com/SapozhnikovMA/yp-project/tree/main/NLP).
  - Необходим о классифицировать отзывы на негативные и положительные. F1 не менее 0,75.
  - Проведена чистка текста с помощью лемматизатора WordNetLemmatizer(выделение лемм, определение части речи, удаление стоп-слов, регулярных выражении);
  - Создание векторов с помощью "мешка слов", TF-IDF;
  - Обучение моделей логистической регрессии и классификаторах LinearSVC, LGBM;

5. [Прогнозирование восстановления золота из руды](https://github.com/SapozhnikovMA/yp-project/tree/main/gold_recovery):
  - По собранным данным, зафиксированных в процесса извлечения золота из руды, необходимо определить зависимости факторов от финального выхода золота;
  - Обучить модели и предсказывать коэффициент восстановления золота из руды;
  - Подготовка признаков к обучению;
  - Визуальный анализ процессов и концетраций других веществ в руде;
  - Обучение моделей и предсказания.
 
6. [Выявление факторов влияющих на стоимость машин](https://github.com/SapozhnikovMA/yp-project/tree/main/price_auto):
  - Разведочный стат. анализ данных, умение корректно готовить данные (дубли, пропуски), исследовательский анализ (аномалии, зависимости, правильные выводы);
  - Построение графиков и поиск закономерностей;
  - с помощью EDA улучшена корреляция числовых показателей с ценой;
  - подготовлены данные для обучения;
  - использованы для сравнения различные модели регрессии.

7. [Определение региона, где добыча нефти принесет наибольшую прибыль, при низком риске](https://github.com/SapozhnikovMA/yp-project/tree/main/oil):
  - Нужно предоставить данные для выбора, где бурить новые скважину;
  - Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов;
  - Постройить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль;
  - Проанализировать возможную прибыль и риски техникой Bootstrap.

8. [Определение пиковой нагрузки и прогноза заказов на следующий час](https://github.com/SapozhnikovMA/yp-project/tree/main/taxi):
  - Определение временной зависимости;
  - Определение тренда и сезонности;
  - Создание функции преобразования датасета со средними и лагами для обучения моделей;
  - Выявление закономерностей и обучение модели catboost, lgbm для предсказаний.

9. [Выбор оптимального тарифа для пользователей](https://github.com/SapozhnikovMA/yp-project/tree/main/telecom_tariff):
  - Предварительный анализ тарифов. Анализ поведение клиентов и выводы — какой тариф лучше.

10. [Определение успешных игр и платформ](https://github.com/SapozhnikovMA/yp-project/tree/main/top_games):
  - Интернет-магазину (продажа компьютерных игр по всему миру) необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании;
  - Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).
