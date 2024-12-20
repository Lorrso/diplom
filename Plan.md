## План тестирования

### 1. Обзор функционала

**Объект тестирования:** мобильное приложение "В Хосписе" <br/>
**Тестовые данные:** Логин, пароль. <br/>
**Реализованный функционал приложения:** <br/>
Работа с аккаунтом
* Авторизация с использованием логина и пароля
* Выход из-под учетной записи

Главная страница
* Отображение новостей в хронологическом порядке
* Отображение заголовка новости
* Возможность развернуть новость
* Отображение описания новости
* Переход по кнопке "Все новости" в раздел Новости

Раздел "Новости"
* Отображение новостей в хронологическом порядке
* Возможность прокрутки ленты
* Отображение заголовка новости
* Возможность развернуть новость
* Отображение описания новости

Панель управления новостями
* Создание новых новостей с выбором категории и даты и времени публикации
* Редактирование существующих новостей
* Изменение активности новости
* Удаление новостей

Фильтрация ленты новостей
* Фильтрация новостей в порядке убывания и возрастания
* Фильтрация новостей по периоду
* Фильтрация новостей по категории
* Фильтрация по активности публикации (только в панели управления новостями)

Тематические цитаты
* Заголовок раздела
* Отображение заголовка цитаты на экране
* Возможность развернуть цитату
* Отображение подзаголовка цитаты на экране
* Возможность прокрутки цитат

Раздел "О приложении"
* Отображение информации о версии приложения
* Ссылка на политику конфиденциальности
* Ссылка на пользовательское соглашение
* Отображение контактных данных компании

### 2. Типы тестирования

**Функциональное тестирование:** <br/>
Проверка корректности обработки данных <br/>
Проверка работоспособности всех функций приложения <br/>
**Тестирование GUI:** <br/>
Проверка визуального оформления приложения <br/>
**Тестирование usability:** <br/>
Проверка удобства использования приложения

### 3. План проверок

#### 3.1. Работа с аккаунтом
* Авторизация:
    * Успешный вход с корректным логином и паролем
    * Сообщение об ошибке при неверном логине или пароле
    * Сообщение об ошибке при пустых полях ввода
    * Сохранение сессии после авторизации
    * Читаемость визуальных элементов экрана авторизации
    * Пароль находится за символами "***"
* Выход из учетной записи:
    * Успешный выход из учетной записи
    * Переход на экран авторизации после выхода
    * Читаемость кнопки выхода из учетной записи

#### 3.2. Главная страница
* Отображение главной страницы:
    * Визуальное оформление шапки страницы
    * Наличие логотипа приложения
    * Отображение кнопки "Тематические цитаты"
    * Отображение кнопки выхода из-под учетной записи
    * Активность кнопки навигации по разделам
* Блок "Новости":
    * Отображение блоков новостей в хронологическом порядке
    * Отображение заголовка публикации
    * Возможность развернуть новость для просмотра описания
* Кнопка "Все новости":
    * Переход в раздел "Новости" при нажатии на кнопку

#### 3.3. Раздел "Новости"
* Отображение новостей:
    * Отображение блоков новостей в хронологическом порядке
    * Отображение заголовка новости
    * Раскрытие описания новости
    * Видимость визуальных элементов навигации раздела
    * Переход на панель управления новостями

#### 3.4. Панель управления новостями
* Создание новостей:
    * Возможность создания и сохранения новости с выбором категории, даты и времени публикации
    * Отображение созданной новости в разделе "Новости"
    * Обязательное заполнение полей "категория", "заголовок", "дата", "время", "описание"
* Редактирование новостей:
    * Редактирование опубликованной новости
    * Снятие новости с публикации
* Удаление новостей:
    * Удаление опубликованной новости
    * Удаление неопубликованной новости

#### 3.5. Фильтрация ленты новостей
* Сортировка:
    * Сортировка новостей по алфавитному убыванию
    * Сортировка новостей по алфавитному возрастанию
    * Визуальное отображение активной сортировки
* Фильтрация:
    * Выбор категории для фильтрации новостей и корректность фильтрации новостей по выбранной категории
    * Выбор периода времени для фильтрации новостей и корректность фильтрации новостей по заданному периоду
    * Фильтрация новостей по статусу публикации (активна/неактивна) в панели управления новостями и корректность фильтрации новостей по выбранному статусу
    * Визуальное отображение активной фильтрации

#### 3.6. Тематические цитаты
* Страница тематических цитат:
    * Отображение заголовка раздела
    * Отображение заголовков цитат
    * Раскрытие описаний к цитатам
    * Корректное форматирование текстов цитат

#### 3.7. Раздел "О приложении"
* Страница с информацией о приложении:
    * Отображение логотипа приложения в шапке раздела
    * Отображение установленной версии приложения
    * Активность ссылки "Политика конфиденциальности"
    * Активность ссылки "Пользовательское соглашение"
    * Отображение контактных данных компании внизу страницы

#### 3.8 Прочее:
* Работа с установкой, удалением и накаткой обновлений:
    * Установка приложения
    * Обновление приложения
    * Удаление приложения
* Работа с сетью:
    * Работа без подключения к сети
    * Восстановление связи
* Навигация:
    * Обработка типовых жестов
    * Системные кнопки навигации (Назад, Дом, Закладки)
* Приостановка работы приложения:
    * Сохранение сессии при сворачивании приложения
    * Реакция на входящие сигналы (СМС, звонок)
    * Выключение телефона

### 4. План автоматизации тестирования

**Инструменты:**

* _Android Studio:_ IDE для автоматизации тестирования мобильных приложений.
* _Espresso:_ Фреймворк для автоматизации тестирования мобильных приложений.
* _UI Automator:_ Инструмент для создания автоматизированных UI-тестов под Android.
* _Allure:_ Инструмент для создания отчетности по итогам прогона тестов.

**Автоматизация функционального тестирования:**

* _Авторизация:_ Создание тестовых сценариев для проверки успешного входа с корректным логином и паролем, а также проверки выдачи сообщений об ошибках при неверном вводе данных.
* _Главная страница:_ Проверка корректного отображения шапки страницы и блока новостей, а также возможности перехода по кнопкам навигации.
* _Раздел "Новости":_ Проверка отображения блока новостей, прокрутки ленты, возможности развернуть новость для просмотра описания и перехода на панель управления новостями.
* _Панель управления новостями:_ Автоматизация создания, редактирования и удаления новостей, проверка корректной обработки операций.
* _Сортировка и фильтрация ленты новостей:_ Проверка корректности работы сортировки в алфавитном порядке и фильтров по категории, дате и активности.
* _Раздел "Тематические цитаты":_ Проверка отображения цитат, возможности их развернуть и прокручивать ленту.
* _Раздел "О приложении":_ Проверка отображения корректной информации о приложении, активность ссылок.

**Устройства для автоматизации:**
* Realme 11 Pro+ 5G

**Директория для автоматизированных тестов:** ./app/src/test/ru/netology/qa

### 5. Сценарии для автоматизированного тестирования

Какие сценарии планируется автоматизировать со ссылкой на id тест-кейса.

### 6. Составление отчетности

По завершению работы над тестированием мобильного приложения планируется создать отчетность по результатам выполнения тестов.

В разметку тестов для отчёта должно входить:
* названия функциональностей;
* описания тестов;
* шаги;
* прикрепление снимков экрана при падении.

**Интервальная оценка времени для проведения тестирования и автоматизации**:
Разработка автотестов и проведение автоматизированного тестирования (с учетом рисков): 18 часов.
Ручное тестирование приложения (с учетом рисков): 5 часов.

Название архива с отчетами о результатах прогона тестов: _allure-results.zip_. <br/>
Название файла с результатом сравнения времени ручного тестирования приложения по чек-листу и UI-тестами: _Result.md_. <br/>
Файл с описанием процедуры запуска авто-тестов: _README.md_.