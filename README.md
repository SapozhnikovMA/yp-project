# Портфолио проектов:
  1. Оптимизация энергопотребления на этапе обработки стали (temp_steel);
  2. Отток клиентов банка (Bank);
  3. Определение возраста покупателей с помощью нейронных сетей (CV);
  4. Проект по определению негативных и положительных отзывов (NLP);
  5. Прогнозирование восстановления золота из руды (gold_recovery);
  6. Выявление факторов влияющих на стоимость машин (price_auto);
  7. Определение региона, где добыча нефти принесет наибольшую прибыль, при низком риске (Oil);
  8. Определение пиковой нагрузки и прогноза заказов на следующий час (Taxi);
  9. Выбор оптимального тарифа для пользователей (telecom_triff);
  10. Определение успешных игр и платформ (Top_games)

# Краткое описание задач и полученных результатов:
1. Оптимизация энергопотребления на этапе обработки стали (temp_steel):
  - Создание новых фичей с помощью groupby, получение нового датасета с помощью pd.merge();
  - разведочный анализ, проверка мультиколлинеарности, создание и обучение моделей предсказания, выбор лучших моделей;
  - Определение важности признаков (features importances) и обоснование использования в моделях;
  - Достигнута целевая метрика MAE < 6, при средней температуре 1591;
  
2.  Отток клиентов банка (Bank):
  - Необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.
  - Построить модель с предельно большим значением F1-меры;
  - Модели не помогут удержать клиентов, но помогут руководству банка принять правильное решение;
  
3. Определение возраста покупателей с помощью нейронных сетей (CV):
  - Подготовка фотографий;
  - Подготовка функций для обучения Resnet50;
  - Анализ моделей.

4. Проект по определению негативных и положительных отзывов (NLP).
  - Классификация отзывов на негативные и положительные. F1 не менее 0,75.
  - Проведена чистка текста с помощью лемматизатора WordNetLemmatizer(выделение лемм, определение части речи, удаление стоп-слов, регулярных выражении);
  - Создание векторов с помощью "мешка слов", TF-IDF;
  - Обучение моделей логистической регрессии и классификаторах LinearSVC, LGBM;
  - Лучшая модель - LinearSVC - 0.79 (С - 0.8), меньше всего ошибок FP и FN;

5. Прогнозирование восстановления золота из руды (gold_recovery):
  - Подготовка признаков к обучению;
  - Визуальный анализ процессов и концетраций других веществ в руде;
  -  Обучение моделей и предсказания.
 
6. Выявление факторов влияющих на стоимость машин (price_auto):
  - Разведочный стат. анализ данных, умение корректно готовить данные (дубли, пропуски), исследовательский анализ (аномалии, зависимости, правильные выводы);
  - Построение графиков и поиск закономерностей;
  - с помощью EDA улучшена корреляция числовых показателей с ценой;
  - подготовлены данные для обучения;
  - использованы для сравнения различные модели регрессии.

7. Определение региона, где добыча нефти принесет наибольшую прибыль, при низком риске (Oil):
  - Нужно решить, где бурить новую скважину;
  - Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов;
  - Постройить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль;
  - Проанализировать возможную прибыль и риски техникой Bootstrap.

8. Определение пиковой нагрузки и прогноза заказов на следующий час (Taxi):
  - Определение временной зависимости;
  - Определение тренда и сезонности;
  - Создание функции преобразования датасета со средними и лагами для обучения моделей;
  - Выявление закономерностей и обучение модели catboost, lgbm для предсказаний.

9. Выбор оптимального тарифа для пользователей (telecom_triff):
  - Предварительный анализ тарифов. Анализ поведение клиентов и выводы — какой тариф лучше.

10. Определение успешных игр и платформ (Top_games):
  - Интернет-магазину (продажа компьютерных игр по всему миру) необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании;
  - Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).
