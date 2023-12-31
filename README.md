# Проект: Отток клиентов
---
**Описание проекта**: 
Из «Бета-Банка» стали уходить клиенты каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

**Цель проекта**: 
Спрогнозировать уход клиент из банка в ближайшее время на основании исторических данных о поведении клиентов и расторжении договоров с банком. 

**Поставленные задачи**:
1. Загрузка и подготовка данных. 
2. Исследование баланса классов, обучение модели без учёта дисбаланса.
3. Улучшение качества модели с учетом дисбаланса классов. Обучение разных моделей и определение лучшей.
4. Проведение финального тестирования.

**Результаты проекта:**

Таким образом, были рассмотрены различные модели для задачи классификации, а также разные стратегии борьбы с дисбалансом классов. Так, были получены лучшие показатели метрик на модели случайного леса с 80 деревьями решений с глубиной 27, при этом дисбаланс классов был учтен с помощью метода взвешивания классов (`class_weight='balanced'`). F1-мера для данной модели достигла своего значения 0.6 на тестовой выборке, а значение ROC-AUC для этой модели на итоговом тестировании стало равным 0.83, что является лучшим результатом.

**Источник данных**: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)