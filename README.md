# TestTaskCFT

## Обзор: ![edit jpg github2](https://user-images.githubusercontent.com/90349622/209761809-acbdb18d-8a84-4836-a02a-5719deea949a.jpg)

### Тестовое задание на позицию стажёра iOS в компании Центр финансовых технологий

#### Общее описание задания:
Необходимо создать приложение Заметки на языке программирования Swift.  
Приложение может быть сделано как в консольном виде, так и в виде
приложения на macOS, iOS.  
Строгих требований к реализации и функциональности нет.

#### Обязательные требования:
* Создание одной простейшей заметки только с текстом
* Редактирование заметки в окне собственного приложения
* Сохранение заметки между сеансами приложения, в любом формате
* При первом запуске приложение должно иметь одну заметку с текстом

#### Необязательные требования (желательно):
* Создание нескольких заметок в приложении
* Выводить список существующих заметок
* Возможность редактирования любой заметки из списка
* Удаление заметок
* Также сохранять все заметки между сеансами

#### Идеи для улучшения:
* Возможность выделять текст курсивом, жирным и т. п.
* Менять шрифт и размер текста
* Вставка картинок

## Реализация:
* Архитектура MVP
* Framework UIKit
* Приложение работает на iOS 15 и выше
* Реализована поддержка iPhone и iPad
* Поддержка темной темы
* Адаптивная верстка кодом с использованием NSLayoutConstraint & Anchors
* UITableView
* UISearchController
* Хранение данных FileManager
