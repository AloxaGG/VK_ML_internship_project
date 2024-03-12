Профильное задание для ML стажировки VK.

**Модель:** CatBoostRanker

**Метрика NDCG:** 0.926

**Обучение:**
1. Обучение без обработки данных. Метрика: 0.926
2. Обучение с обработкой данных (были удалены константные и коррелирующие признаки). Метрика: 0.909

**Итоги:**

Поставленная задача была успешно решена. Улучшить качество модели затруднительно, т.к. имеется сильный дисбаланс классов и отсутствуют описания фичей. В целом, модель градиентного бустинга catboost хорошо справилась с данной задачей ранжирования. Метрика посчитана при помощи встроенной функции catboost.
