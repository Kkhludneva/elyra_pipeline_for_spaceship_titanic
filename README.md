# Pipeline description
Работа состоит из 3х этапов:
1. Отчистка входных данны - st_preprocessing.ipynb. Подготовленные данные сохраняются в дирректорию data/prepared
2. Решение задачи классификации разыми моделями: логистическая регрессия, random forest, catboost. Веса, присвоенные моделями признакам, сохраняются в model_results
3. Анализ важности признаков на основе файлов из model_results. Постоение графика feature_importances.png