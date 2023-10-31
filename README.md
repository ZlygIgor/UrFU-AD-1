# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Злыгостев Игорь Сергеевич
- РИ221001
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Устновить Anaconda, заупустить Jupiter Notebook, написать код

```py

print("Hellow world")

```

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.

- Устанавливаем Unity и компоненты с официального сайта, пишем нужный код в файл с названием HelloWorld
```C#

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Hello World!!")
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}


```

-В Unity создаём объект и подключаем к нему файл HelloWorld
-Нажимаем конпоку Run и сообщение выводится в консоль

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Копируем пример отчёта [с репозитория](https://github.com/Den1sovDm1triy/DA-in-GameDev-lab1/blob/main/README.md).
- Заполняем отчёт в соответсвии с выполненным заданием


## Выводы

В ходе выполнения работы мы узнали как создавать проекты в Jupiter Notebook и Unity, и соответсвенно создали проекты Hellow world в обоих програмных обеспечениях

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
