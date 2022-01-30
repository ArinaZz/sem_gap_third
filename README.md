# Интерпретация и обработка сигналов

## Третья мини-лабораторная

Лабораторная состоит из пяти заданий, из которых обязательно сделать 3 первых задания,
чтобы лабораторная была зачтена. За каждое следующее выполненное задание даются
дополнительные баллы.

Задание 4 (про аугментацию данных) - дополнительное. Оно повышенной сложности,
на него потребуется затратить больше времени, но за него можно получить 3
дополнительных балла.

Задание 5 - дополнительное, за него можно получить 1 дополнительный балл.

Если решение вошло в топ-3 (среди других решений) по качеству классификации в задании 3, 4 или 5, даются дополнительные баллы,
по одному баллу за каждое из решений, попавших в топ-3. Итоги по дополнительным баллам за попадание в топ-3 по заданиям 3, 4 и 5
подводятся после дедлайна на дополнительные задания.

### Настройка репозитория

1. Сделайте свою **приватную** копию репозитория.
Как это сделать, описано [тут](https://gist.github.com/0xjac/85097472043b697ab57ba1b1c7530274)
или [тут](https://stackoverflow.com/questions/10065526/github-how-to-make-a-fork-of-public-repository-private).

2. Добавьте проверяющих в коллабораторы. GitHub логины: `naschastliv`, `vikto9494`.

### Отправка задания

Аналогично предыдущей мини-лабораторной:

1. Выполните задания, сохраните изменения, сделайте `commit`
и `push` в свой репозиторий.

2. Будет проверяться ветка `main`. В ней должен быть
изменённый файл `third_machine_learning.ipynb` и все добавленные вами
файлы:
    * Чекпойнт `fashion_model.h5` и предсказания `submission.npy`
    * Папка `catboost_info`

Файлы `fashion_images.npy`, `fashion_labels.npy`, `test_fashion_images.npy`,
`val_fashion_images.npy`, `val_fashion_labels.npy` добавлять в репозиторий
не нужно!

Папку, которую `keras-tuner` создаёт в процессе подбора гиперпараметров, добавлять в репозиторий не нужно!

3. Напишите на почту schastlivtsevna@yandex.ru
письмо с темой вида `[MiniLab 3][Фамилия Инициалы]`
с просьбой проверить работу.
В письме должна быть ссылка на репозиторий с
выполненной работой, проверяться будет версия,
которая лежит в ветке `main`.
Репозиторий должен быть приватным;
в ветке `main` не должно быть файлов и папок с русскими
названиями!

### Дедлайн

Дедлайн на обязательные задания: 23:59 23/02/2022.

Дедлайн на дополнительные задания: 23:59 02/03/2022.

Базовая оценка: 3 балла (+ баллы за дополнительные задания).
