# Определение возраста покупателей

## Цель
Постройте модель, которая по фотографии определит приблизительный возраст человека.

## Вывод
Обученная модель продемонстрировала MAE на валидационной выборке 6.5, что ниже целевого значения 8.
Были использованы следующие ключевые допущения: 
  - применена архитектура ResNet50; 
  - использован алгоритм Adam с lr=0.0003; 
  - количество изображений в батче - 16; 
  - выборка поделена на обучающую и валидационную в соотношении 3:1; 
  - функция активации Relu;
  - аугментация не дала уменьшения целевой метрики, поэтому в финальные параметры модели она не была включена.

## Используемые библиотеки
pandas, matplotlib, keras, numpy

## Статус проекта
Завершен

