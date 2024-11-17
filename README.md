# Курс по искусственному интеллекту и машинному обучению (SSAU)

## Практика 2
Построить регрессию для заданного класса между заданными параметрами.
## Практика 4
1. Загрузить датасет WINE.
2. Подготовить выборки: обучающую 70% и тестовую 30%.
3. Построить указанные в задании классификаторы.
4. Применить указанные классификаторы к каждой паре из указанных в варианте задания признаков.
5. Построить разделяющие границы для каждого классификатора и каждой пары признаков.
6. Выбрать наилучшую комбинацию пару признаков и классификатора.
7. Сделать вывод.
## Практика 5
1. Загрузить датасет WINE.
2. Подготовить выборки: обучающую 70% и тестовую 30%.
3. Построить указанные в задании классификаторы.
4. Провести анализ главных компонент с числом компонент =2.
5. Получить оценку качества классификации в новом пространстве признаков с использованием указанных классификаторов.
6. Провести линейный дискриминантный анализ путем построения одного признака.
7. Получить оценку качества классификации для построенного признака с использованием указанных классификаторов.
8. Сравнить результаты классификации в п5 и п 7 с лучшей парой признаков и классификатором из Задания 4.
9. Сделать вывод.
## Практика 6
1. Постройте дерево решений минимальной высоты, которое дает точные предсказания исхода игры для различных условий.
![image](https://github.com/user-attachments/assets/2b42aba0-406e-4340-99ec-2740faa294a1)
## Практика 7
1. Загрузить датасет WINE. Использовать только признаки указанные в варианте задания.
2. Подготовить выборки: обучающую 70% и тестовую 30%.
3. Построить дерево решений обеспечивающее наибольшую точность классификации.
4. Построить случайный лес наименьшей высоты обеспечивающий наибольшую точность классификации.
5. Построить оптимальный случайный лес наименьшей высоты и с минимальным количеством деревьев обеспечивающий наибольшую точность классификации.
6. Получить оценку качества классификации с использованием указанных классификаторов.
7. Сравнить результаты классификации и сделать вывод.
## Практика 8
1. Загрузить датасет WINE.
2. Подготовить выборки: обучающую 70% и тестовую 30%.
3. Для указанных в задании классификаторов с использованием обучающей выборки выбрать 2 компоненты вектора признаков (2 признака), обеспечивающие наилучшее качество классификации.
4. Получить оценку качества классификации с использованием тестовой выборки.
5. Сравнить выбранные признаки для каждого из классификаторов и сделать вывод.
6. Название выбранные признаков для каждого классификатора, а также результаты классификации и вывод записать.
## Практика 9.1
1. Построить сеть, с минимальным количеством нейронов, обеспечивающую accuracy = 1 для следующих данных
```
X = np.arange(10).reshape(-1, 1)
y = np.array([0., 0., 1., 0., 0., 1., 1., 1., 1., 1.])
y = to_categorical(y)
```
