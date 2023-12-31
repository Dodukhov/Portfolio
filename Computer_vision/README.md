# Обработка фотографий покупателя
[ipynb](https://github.com/Dodukhov/Portfolio/blob/main/Computer_vision/computer_vision.ipynb)
## Описание проекта
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

Необходимо построить модель,которая по фотографии определит приблизительный возраст человека.
## Навыки и инструменты
- Python;
- Keras.
## Вывод
После обучения модели мы получили значение MAE равное 6.6, что соответствует порогу и свидетельствует о работоспособности модели. Также, по процессу обучения, а именно понижению метрики на валидационной выборке, можно сделать вывод, что модель демонстрирует улучшение производительности на валидационных данных вместе с уменьшением потерь и MAE по мере увеличения количества эпох.Эксперементально подобрано оптимальное количество эпох, равное 5, которое дает оптимальные значения метрик для работоспособности модели. Также, возвращаясь к задачам, функционирующая модель способна выполнить обе поставленные задачи-как определение возраста для предложения покупок, так и дополнительная проверка кассиров на предмет продажи запрещенных для несовершеннолетних вещей.
