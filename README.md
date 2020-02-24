# MSU_DM_autumn_2019

## HW 1 - KNN
Реализовать KNN в классе MyKNeighborsClassifier (обязательное условие: точность не ниже sklearn реализации).
Реализовать аналог score из KNeighborsClassifier в своём классе. Score не должен уступать значению KNN из sklearn. 
Добиться скорости работы на fit, predict и predict_proba сравнимой со sklearn для iris. 

Добавить algorithm='kd_tree' в реализацию KNN (KDTree из sklearn.neighbors). 
Необходимо добиться скорости работы на fit, predict и predict_proba сравнимой со sklearn для iris. 
Score не должен уступать значению KNN из sklearn.

## HW 2 - Linear Models
Реализация своего батч-генератора, линейного классификатора и логистической регрессии

## HW 3 - Decision Tree
Реализация дерева должна работать по точности не хуже DecisionTreeClassifier из sklearn. 
Точность проверяется на wine и Speed Dating Data. 
Добиться скорости работы на fit не медленнее чем в 10 раз sklearn на данных wine и Speed Dating Data.
Добавить функционал, который определяет значения feature importance.

С помощью GridSearchCV или RandomSearchCV подобрать наиболее оптимальные параметры
для случайного леса (Выбрать 2-3 параметра). Используем данные Speed Dating Data. 

## HW 4 - Clasterization
Алгоритм кластеризации должен удовлетворять следующему интерфейсу.
Конструктор принимает набор параметров, необходимых для работы алгоритма кластеризации.
Метод fit подсчитывает параметры модели и возвращает self.
Метод predict возвращает вектор с индексами кластеров для поданных в него объектов x.

