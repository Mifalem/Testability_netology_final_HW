## Тестирование возможности записаться на обучение профессии «Тестировщик ПО».

### Перечень автоматизируемых сценариев.

1. #### Навигация по сайту  **[нетология](https://netology.ru/).
Способы попасть на страницу профессии "Тестировщик ПО":

* Способ 1:

    1. [ ] В блоке направления обучения кликнуть кнопку "Программирование".
    2. [ ] В открывшемся окне проскролись вниз и кликнуть "Тестировщик ПО".
    3. [ ] Кликнуть "Записаться".

* Способ 2:

    1. [ ] В блоке направления обучения проскролить вниз и кликнуть кнопку "Полный каталог".
    2. [ ] В блоке все курсы кликнуть кнопку "Программирование".
    3. [ ] Проскролить вниз и кликнуть "Тестировщик ПО".
    4. [ ] Кликнуть "Записаться".

* Способ 3:

    1. [ ] Кликнуть кнопку "Каталог курсов".
    2. [ ] В поле "Какой курс вам нужен?" напечатать "тест" и во всплывшем контекстном меню кликнуть "Тестировщик ПО".
    3. [ ] Кликнуть "Записаться".

* Способ 4:

    1. [ ] Кликнуть кнопку "Каталог курсов".
    2. [ ] В поле "Какой курс вам нужен?" напечатать "тест".
    3. [ ] Кликнуть "Найти курс".
    4. [ ] В нижеприведенном списке кликнуть "Тестировщик ПО".
    5. [ ] Кликнуть "Записаться".

* Способ 5:
    1. [ ] Кликнуть кнопку "Каталог курсов".
    2. [ ] Кликнуть "Найти курс".
    3. [ ] В правой части странице в меню "С документами" поставить чекбокс "Диплом о ПП".
    4. [ ] В правой части странице в меню "Навыки" проскролить ниже и поставить чекбокс "Тестирование ПО".
    5. [ ] Проскролить вверх и в предложенных курсах кликнуть "Тестировщик ПО".
    6. [ ] Кликнуть "Записаться".

2. #### Тест-кейсы
    * Позитивные кейсы.
    * Негативные кейсы.

[Ссылка на google документ с тест-кейсами](https://docs.google.com/spreadsheets/d/14iYpwO5VVHf3h8DhdiJKWBsiE4V8ZxQZzbCrzSJZb80/edit?usp=sharing).

### Перечень используемых инструментов с обоснованием выбора.

1. Интерфейс браузера. Через него мы работаем с сайтом.
2. Язык программирования Java, JavaScript, для просмотра данных в devtools и умения писать код.
3. [IntelliJ IDEA](https://www.jetbrains.com/ru-ru/idea/), для написания когда тестирования.
4. [Postman](https://www.postman.com/), для тестирования клент-серверного взаимодействия, отправляется ли форма, какие статусы и т.д.
5. [Git](https://git-scm.com/), для ведения (управления) кода(ом) на локальном ПК.
6. [GitHub](https://github.com/), для отправки кода программы или данных в облако, чтобы другие пользователи могли взаимодействовать с ним.
7. [Apache JMeter](https://jmeter.apache.org/), для испытывания сервера под нагрузкой.

### Перечень необходимых разрешений, данных и доступов.
1. Возможно ли проводить автотестирование включая нагрузочное тестирование.
2. Данные тестовых пользователей (если они есть), если нет, то возможно ли использовать реальных пользователей.
3. Доступ к API, ключам API, БД, чтобы понимать появился ли пользователь в базе данных после отправки формы. Можно ли удалить пользователя из БД при ошибочной записи.

### Перечень и описание возможных рисков при автоматизации.
1. Изменение структуры сайта может привести к тому что придется менять код тестирования.
2. Изменение интерфейса сайта приведет к тому что необходимо будет менять тест-кейсы.
3. При нагрузочном тестировании возможно падение сервера. 

### Перечень необходимых специалистов для автоматизации.
* Автотестировщик.

### Интервальная оценка с учётом рисков в часах.
* В связи с наличием некоторого количества рисков связанных с тестированием необходимо к расчетному времени подготовки к тестированию и его проведения прибавить не менее 25% времени.
