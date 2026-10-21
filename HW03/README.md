# Homework 3 — обучение аудиопредставлений

[Выполненный notebook](https://github.com/avalanche-zxc/urfu-dls-speech/blob/main/HW03/Cheremisin_Speech_HW3_Self_Supervised.ipynb) · [Открыть в Colab](https://colab.research.google.com/github/avalanche-zxc/urfu-dls-speech/blob/main/HW03/Cheremisin_Speech_HW3_Self_Supervised.ipynb)

Использован полный AudioMNIST: 24 000 обучающих записей от 48 дикторов и 6 000 проверочных от других 12 дикторов. Supervised обучен 15 эпох, InfoNCE — 20, VICReg — 30. У трёх методов одинаковая проверка: замороженные энкодеры, объединение 128 признаков и линейный классификатор, обученный только на train.

- supervised: 5939/6000, accuracy 98.9833%, macro F1 0.9898
- infonce: 5626/6000, accuracy 93.7667%, macro F1 0.9377
- vicreg: 5706/6000, accuracy 95.1000%, macro F1 0.9513

Notebook содержит код, вычисленные выводы, шесть графиков, анализ VICReg и ограничения эксперимента. Это один seed и одно разбиение; отдельного тестового набора нет. Использование ИИ раскрыто в notebook.

В чистом Colab скачивается около 1 ГБ AudioMNIST и запускается обучение; рекомендуется GPU. Датасет и локальные checkpoint в репозиторий не включены. Существующие checkpoint при повторном локальном запуске используются явно; RUN_FRESH=True запускает обучение заново. Точное совпадение чисел на другом GPU не гарантировано.

[Исходное задание](https://github.com/DeepLearningSchool/Speech/blob/main/week_03_speech_ssl/Homework/SSL_Homework.ipynb).

Публикация не подтверждает сдачу в eLearn или официальный процент прохождения курса.
