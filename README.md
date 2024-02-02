## Ансамбль стеккинга
![image](https://github.com/Sadm1sh/The-Stacking-Ensemble/assets/116463567/5a5038b5-074f-4e75-b2fc-7709ae5a9d64)

### Постановка задачи:
Загрузите данные, приведите их к числовым, заполните пропуски, нормализуйте данные и оптимизируйте память.

Сформируйте параллельный ансамбль из CatBoost, градиентного бустинга, XGBoost и LightGBM.
Используйте лучшие гиперпараметры, подобранные ранее, или найдите их через перекрестную проверку.
Итоговое решение рассчитайте на основании самого точного предсказания класса у определенной модели ансамбля: выберите для каждого класса модель, которая предсказывает его лучше всего.

Проведите расчеты и выгрузите результат в виде submission.csv

Данные:
* train: video.ittensive.com/machine-learning/prudential/train.csv.gz
* test: video.ittensive.com/machine-learning/prudential/test.csv.gz
* submission: video.ittensive.com/machine-learning/prudential/sample_submission.csv.gz
