# Countries (Мировые страны)

## Описание задачи:
Разработать приложение “Мировые страны”, которое позволяет пользователю просматривать информацию о различных странах мира. Приложение должно быть создано с использованием **SwiftUI** и демонстрировать различные аспекты iOS-разработки. Для получения данных необходимо использовать **API REST Countries**, основываясь на предоставленном JSON.

## Основные требования
### Главный экран:
- [ ] Отобразить список стран в виде **вертикального списка**.
- [ ] Каждая ячейка страны должна содержать:
- [ ] - Название страны.
- [ ] - Флаг страны.
- [ ] - Регион (континент).
- [ ] Реализовать **поиск по названию страны**.

### Детальный экран страны:
- [ ] При выборе страны отображать подробную информацию:
- [ ] - Официальное название (official).
- [ ] - Столица (capital).
- [ ] - Население (population).
- [ ] - Площадь (area).
- [ ] - Валюта (название и символ из currencies).
- [ ] - Языки (languages).
- [ ] - Часовые пояса (timezones).
- [ ] - Координаты (latlng) с отображением на карте
(используя MapKit).
- [ ] - Флаг страны в большем размере.
- [ ] Возможность добавить страну в **“Избранное”**
- [ ] - Реализовать функцию **“Поделиться”** информацией о
стране через **UIActivityViewController** или **ShareLink**.

### Избранные страны:
- [ ] Отдельный раздел для отображения списка избранных
стран.
- [ ] Возможность удаления стран из избранного.

### Сетевые запросы и работа с API:
- [ ] Получать данные о странах из **REST Countries API**.
- [ ] Использовать структуру данных, аналогичную
предоставленному JSON.
- [ ] Слой сетевых запросов к API должен быть реализован
через **URLSession**.
- [ ] Для загрузки и кэширования изображений флагов
можно использовать сторонние библиотеки.
- [ ] **Важно:** Все сетевые операции должны выполняться
асинхронно, чтобы интерфейс не подвисал. При загрузке
данных отображать индикаторы активности (лоадеры)
там, где это необходимо.

### Локальное хранение данных:
- [ ] Сохранять избранные страны с использованием **Core Data**
или **SwiftData**.
- [ ] **Кэшировать данные** для работы в **офлайн-режиме**.

### Интерфейс пользователя:
- [ ] Использовать **SwiftUI** для построения интерфейса.
- [ ] Приложение должно поддерживать **светлую и темную
тему**.
- [ ] Адаптивный дизайн для разных размеров экрана.
- [ ] Все цвета в приложении должны храниться в
каталогах **xcassets**.
- [ ] Важно: При загрузке элементов **интерфейс не должен
подвисать**. Обеспечить плавную работу приложения.

### Локализация:
- [ ] Реализовать **поддержку минимум двух языков**: русского и
английского.
- [ ] Все **текстовые элементы должны быть локализованы**.
- [ ] Использовать данные из раздела **translations** для
**отображения названий стран на разных языках**.
- [ ] Желательно: Для локализаций использовать новый
формат **.xcstrings**.

### Обработка ошибок:
- [ ] Предусмотреть **обработку возможных ошибок сети** и
**отображение соответствующих сообщений** пользователю.
- [ ] **Обрабатывать ситуации отсутствия интернет-соединения**.
- [ ] Важно: Все ошибки должны обрабатываться корректно,
без вылетов приложения. При возникновении ошибок
показывать пользователю соответствующие **алерты**,
чтобы пользователь понимал, что происходит.

### Архитектура и конфигурация:
- [ ] Приложение должно быть построено с использованием
архитектурного паттерна **MVVM** или **TCA**.
- [ ] Код должен быть **чистым**, **организованным** и **легко
поддерживаемым**.
- [ ] Важно: Все константы, ссылки на API и ключи должны
храниться в файлах **.xcconfig** для удобства настройки и
безопасности.

### Дополнительные требования (по желанию):
- [ ] Использовать **Swift Package Manager** для подключения
сторонних библиотек.
- [ ] Интегрировать виджеты для экрана **“Сегодня”** с
информацией об избранных странах.

## Что необходимо предоставить:
- [ ] Ссылку на репозиторий с исходным кодом (GitHub, Bitbucket
и т .д.).
- [ ] Инструкции по сборке и запуску проекта в файле
README.md.
- [ ] Краткое описание использованных технологий и решений.

## Критерии оценки:
* Соответствие выполненного задания поставленным
требованиям.
* Качество и чистота кода (стилистика, именование, структура
проекта).
* Грамотное использование возможностей SwiftUI и других
технологий.
* Удобство и отзывчивость интерфейса пользователя.
* Способность обрабатывать ошибки и исключения,
информируя пользователя через соответствующие алерты.
* Наличие комментариев и документации в коде.
* Креативность и инициативность в реализации
дополнительных функций.
* Важно: Приложение должно работать плавно, без
подвисаний. При загрузке данных интерфейс не должен
зависать; необходимо показывать индикаторы загрузки там,
где это уместно.
