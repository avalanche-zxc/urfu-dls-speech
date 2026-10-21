# DLS Speech — учебные работы

Решения Михаила Черемисина по курсу обработки звука и речи Deep Learning School, подготовленные для онлайн-траектории курса «Искусственный интеллект и нейронные сети» в магистратуре УрФУ.

## Homework 2 — спектры, STFT и mel-спектрограммы

[Notebook с результатами](https://github.com/avalanche-zxc/urfu-dls-speech/blob/main/HW02/DLS_HW2_Spectrograms_Cheremisin.ipynb) · [Открыть в Google Colab](https://colab.research.google.com/github/avalanche-zxc/urfu-dls-speech/blob/main/HW02/DLS_HW2_Spectrograms_Cheremisin.ipynb)

В работе сопоставляются гармоники музыкальных инструментов, классификация по исходной волне и амплитудному спектру, окна при STFT и собственное mel-преобразование. Notebook выполнен локально, выводы и девять графиков сохранены. Все пять ячеек также выполнены в чистой среде Google Colab без ошибок.

В выданных данных оказалось 9 записей скрипки, 3 флейты и 3 виолончели вместо 10 каждого инструмента. Использованы все 15 предоставленных записей; недостающие записи не дублировались. Ограничение явно описано в работе. На тесте из шести записей спектр дал 5 верных ответов, исходная волна — 4; выборка слишком мала для широких выводов.

Notebook содержит получение исходных открытых данных и проверки mel-фильтров относительно librosa. Большие датасеты не включены в репозиторий. Использование ИИ при подготовке решения раскрыто в notebook.

[Оригинальное задание DLS](https://github.com/DeepLearningSchool/Speech/blob/main/week_02_speech_representations/Homework/unsolved_DLS_HW2__Beyond_the_Fundamental_A_Spectral_Adventure.ipynb).

Публикация в GitHub сама по себе не подтверждает сдачу или оценку в УрФУ. Процент прохождения курса по этим материалам пока не установлен.

## Homework 3 — самообучение аудиопредставлений

[Notebook](https://github.com/avalanche-zxc/urfu-dls-speech/blob/main/HW03/Cheremisin_Speech_HW3_Self_Supervised.ipynb) · [Результаты и воспроизведение](HW03/README.md) · [Colab](https://colab.research.google.com/github/avalanche-zxc/urfu-dls-speech/blob/main/HW03/Cheremisin_Speech_HW3_Self_Supervised.ipynb)

Три подхода обучены на полном AudioMNIST; одинаковая проверка на новых дикторах. Подготовлено, в eLearn не отправлено.
