### Задание 2 - 10 баллов

- Загрузить набор данных [Spam Or Not Spam](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset)
- Попробовать и сравнить различные способы векторизации: **3 балла**
  - `sklearn.feature_extraction.text.CountVectorizer`
  - `sklearn.feature_extraction.text.TfidfVectorizer`
- Обучить на полученных векторах модели, с использованием кросс-валидации и подбором гиперпараметров: **3 балла**
  - `sklearn.tree.DecisionTreeClassifier`
  - `sklearn.linear_model.LogisticRegression`
  - Naive Bayes
- Сравнить качество обученных моделей на отложенной выборке - **1 балл**

- Обеспечена воспроизводимость решения: зафиксированы random_state, ноутбук воспроизводится от начала до конца без ошибок - **2 балла**

- Соблюден code style на уровне pep8 и [On writing clean Jupyter notebooks](https://ploomber.io/blog/clean-nbs/)  - **1 балл**