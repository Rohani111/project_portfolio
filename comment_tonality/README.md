# Обучение модели классификации комментариев

## Цель
Обучите модель классифицировать комментарии на позитивные и негативные.

## Вывод
 * в первую очередь стоит отметить, что все обученные модели продемонстрировали точность в разы лучше, нежели константаная модель, которая все комментарии расценивала как токсичные;
 * **наибольшую точность продемонстрировала модель градиентного бустинга Catboost**, чуть хуже модели градиентного бустинга LightGBM и линейной регрессии;
 * На основании матрицы ошибок мы видим, что выбранная нами модель почти на 60% лучше в определении токсичности комментариев, нежели константная модель, для которой recall равен 10%.

## Используемые библиотеки
pandas, matplotlib, nltk, re, scikit-learn

## Статус проекта
Завершен
