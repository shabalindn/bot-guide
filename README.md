# Slowpoke Training Bot

Бот для замеров и рекордов

<img src="./img/menu.jpeg" alt="menu" width="300"/>

## Команды

1. [Замеры](#measure)
    - [Список последних замеров](#measure-last-list)
    - [Список замеров](#measure-list)
    - [Добавить замер](#measure-add)
    - [Изменить замер](#measure-update)
    - [Удалить замер](#measure-delete)
2. [Рекорды](#record)
    - [Группы рекордов](#record-group-list)
    - [Рекорды одной группы](#record-list)
    - [Рекорд](#record)
    - [Добавить рекорд](#record-add)
    - [Изменить рекорд](#record-update)
    - [Удалить рекорд](#record-delete)
3. [Настройки](#settings)
    - [Уведомления](#settings-notification)
    - [Замеры](#settings-measure)
4.  [Экспорт данных](#export)
5. [О боте](#info)



## Замеры <a name="measure"></a>
Команда позволяет добавлять, изменять и обновлять замеры тела.


### Список последних замеров <a name="measure-last-list"></a>
<img src="./img/measure-last-list.jpeg" alt="measure-last-list" width="300"/>

Чтобы посмотреть список последних замеров, выберите команду *Замеры* в меню или введите `/measure`.

> Показываются только те замеры, которые выбраны в настройках

### Список замеров <a name="measure-list"></a>
<img src="./img/measure-list.jpeg" alt="measure-list" width="300"/>

Выберите один замер, например *Вес*, чтобы увидеть историю значений замера. В сообщении указано общее количество значений замеров.

> На каждой странице по 5 записей

### Добавить замер <a name="measure-add"></a>
Добавить значение замера можно несколькими способами:
- [Добавить сегодня](#measure-add-today)
- [Быстрое добавление](#measure-add-fast)
- [Добавить в другой день](#measure-add-calendar)

> Если значение замера уже есть на эту дату, то его значение будет обновлено

#### Добавить сегодня <a name="measure-add-today"></a>
1. Выберите замер из списка замеров
2. Нажмите кнопку *Добавить сегодня*
3. Введите числовое значение
4. Значение замера будет добавлено в список сегодняшним днем

#### Быстрое добавление <a name="measure-add-fast"></a>
1. Выберите замер из списка замеров
2. Введите числовое значение
3. Значение замера будет добавлено в список сегодняшним днем

#### Добавить в другой день <a name="measure-add-calendar"></a>
<img src="./img/calendar.jpeg" alt="calendar" width="300"/>

1. Выберите замер из списка замеров
2. Нажмите кнопку *Добавить в другой день*
3. Выберите день в календаре
4. Введите числовое значение
5. Значение замера будет добавлено в список


### Изменить замер <a name="measure-update"></a>
Изменить значение замера можно несколькими способами:
- [Изменить значение](#measure-update-base)
- [Быстрое изменение](#measure-update-fast)

#### Изменить значение <a name="measure-update-base"></a>
1. Выберите замер из списка замеров
2. Выберите значение замера, которое хотите изменить
3. Нажмите кнопку *Изменить*
4. Введите числовое значение
5. Значение замера изменится

#### Быстрое изменение <a name="measure-update-fast"></a>
1. Выберите замер из списка замеров
2. Выберите значение замера, которое хотите изменить
3. Введите числовое значение
4. Значение замера изменится


### Удалить замер <a name="measure-delete"></a>
<img src="./img/measure-delete.jpeg" alt="measure-delete" width="300"/>

1. Выберите замер из списка замеров
2. Выберите значение замера, которое хотите удалить
3. Нажмите кнопку *Удалить*
4. Подтвердите удаление замера
5. Значение замера удалится



## Рекорды <a name="record"></a>

Команда позволяет добавлять, изменять и обновлять рекорды.
Выберите команду *Рекорды* в меню или введите `/record`.

### Группы рекордов <a name="record-group-list"></a>
<img src="./img/record-group-list.jpeg" alt="record-group-list" width="300"/>

Рекорды разделены в группы по правилам выполнения упражнения

> Показываются все доступные группы рекордов


### Рекорды одной группы <a name="record-list"></a>
<img src="./img/record-list.jpeg" alt="record-list" width="300"/>

После выбора группы отображаются рекорды в составе этой группы

> Показываются все доступные рекорды


### Список значений рекордов <a name="record"></a>
<img src="./img/record.jpeg" alt="record" width="300"/>

Выберите один рекорд, например *Отжимания*, чтобы увидеть историю значений рекорда. В сообщении указано общее количество значений рекорда.

> На каждой странице по 5 записей


### Добавить рекорд <a name="record-add"></a>
Добавить значение рекорда можно несколькими способами:
- [Добавить сегодня](#record-add-today)
- [Быстрое добавление](#record-add-fast)
- [Добавить в другой день](#record-add-calendar)

> Если рекорд уже есть на эту дату, то его значение будет обновлено

#### Добавить сегодня <a name="record-add-today"></a>
1. Выберите рекорд из списка рекордов
2. Нажмите кнопку *Добавить сегодня*
3. Введите числовое значение
4. Значение рекорда будет добавлено в список сегодняшним днем

#### Быстрое добавление <a name="record-add-fast"></a>
1. Выберите рекорд из списка рекордов
2. Введите числовое значение
3. Значение рекорда будет добавлено в список сегодняшним днем

#### Добавить в другой день <a name="record-add-calendar"></a>
<img src="./img/calendar.jpeg" alt="calendar" width="300"/>

1. Выберите рекорд из списка рекордов
2. Нажмите кнопку *Добавить в другой день*
3. Выберите день в календаре
4. Введите числовое значение
5. Значение рекорда добавиться в список


### Изменить рекорд <a name="record-update"></a>
Изменить значение рекорда можно несколькими способами:
- [Изменить значение](#record-update-base)
- [Быстрое изменение](#record-update-fast)

#### Изменить значение  <a name="record-update-base"></a>
1. Выберите рекорд из списка рекордов
2. Выберите значение рекорда, которое хотите изменить
3. Нажмите кнопку *Изменить*
4. Введите числовое значение
5. Значение рекорда изменится

#### Быстрое изменение  <a name="record-update-fast"></a>
1. Выберите рекорд из списка рекордов
2. Выберите значение рекорда, которое хотите изменить
3. Введите числовое значение
4. Значение рекорда изменится


### Удалить рекорд <a name="record-delete"></a>
<img src="./img/record-delete.jpeg" alt="record-delete" width="300"/>

1. Выберите рекорд из списка рекордов
2. Выберите значение рекорда, которое хотите удалить
3. Нажмите кнопку *Удалить*
4. Подтвердите удаление рекорда
5. Значение рекорда удалиться




## Настройки <a name="settings"></a>
<img src="./img/settings.jpeg" alt="settings" width="300"/>

Команда *Настройки* в меню или введите `/settings`

Доступны настройки:
- [Настройки: уведомления](#settings-notification)
- [Настройки: замеры](#settings-measure)

### Настройки: уведомления <a name="settings-notification"></a>
<img src="./img/settings-notification.jpeg" alt="settings-notification" width="300"/>

Можно выбрать периодичность уведомления о замерах или отключить уведомление о замерах


### Настройки: замеры <a name="settings-measure"></a>
<img src="./img/settings-measure.jpeg" alt="settings-measure" width="300"/>

Можно выбрать нужные замеры

> Выбранные замеры в квадратных скобочках


### Экспорт данных <a name="export"></a>

<img src="./img/export.jpeg" alt="export" width="300"/>

Команда *Экспорт данных* в меню или введите `/export`
Можно экспортировать замеры, рекорды за все время или за год

<img src="./img/export-measure-2024.jpeg" alt="export-measure-2024" width="300"/>

В ответ вы получите файл с расширением  `csv`

## О боте <a name="info"></a>
<img src="./img/info.jpeg" alt="info" width="300"/>

Содержит ссылку на эту инструкцию, версию и описание бота, ссылку на разработчика
