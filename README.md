# Мои проекты по Data Science и машинному обучению

Репозиторий с учебными проектами. Каждый проект оформлен в виде Jupyter Notebook с полным кодом и выводами.

## Список проектов

| Название | Описание | Технологии | Ссылка |
|----------|----------|------------|--------|
| **Классификация токсичных комментариев** | Бинарная классификация текстов. Предобработка (токенизация, лемматизация, POS-теги), TF-IDF, подбор гиперпараметров, LightGBM. Метрика F1-score ~0.75. | `pandas`, `nltk`, `scikit-learn` (TfidfVectorizer, RandomizedSearchCV), `lightgbm.LGBMClassifier`, `tqdm`, `re` | [Ноутбук](https://github.com/Ruslani0/-Data-Science-Project/blob/main/Машинное_обучение_для_текстов.ipynb) |
| **Прогноз заказов такси** | Временные ряды: создание лагов, скользящих средних, признаков даты. Модели: RandomForest, DecisionTree, LGBMRegressor. Оценка RMSE. | `pandas`, `matplotlib`, `scikit-learn` (GridSearchCV, TimeSeriesSplit, RandomForestRegressor, ColumnTransformer), `statsmodels` (seasonal_decompose), `lightgbm.LGBMRegressor` | [Ноутбук](https://github.com/Ruslani0/-Data-Science-Project/blob/main/Временные_ряды.ipynb) |
| **Анализ олимпиадных данных «Стальная птица»** | Разведочный анализ, визуализация, проверка гипотез, корреляционный анализ (phik), регрессионные модели (CatBoost, RandomForest, LinearRegression). | `pandas`, `seaborn`, `matplotlib`, `scipy.stats`, `phik`, `statsmodels` (VIF), `scikit-learn` (предобработка, метрики, GridSearchCV), `catboost.CatBoostRegressor` | [Ноутбук](https://github.com/Ruslani0/-Data-Science-Project/blob/main/Проект_стальная_птица.ipynb) |

