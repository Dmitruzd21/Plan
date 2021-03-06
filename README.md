# **План тестирования возможности записи на курс “Тестировщик ПО” сайта нетологии**

## **Перечень автоматизируемых сценариев**

**ТЕСТИРОВАНИЕ СЦЕНАРИЕВ ПЕРЕХОДА НА СТРАНИЦУ ПРОФЕССИИ “ТЕСТИРОВЩИК ПО”**

ОР для всех групп: успешный переход на страницу профессии.

**Группа 1**

1. Каталог курсов, Программирование (клик), Тестировщик ПО (выбор из списка)

**Группа 2**

1. Каталог курсов, Программирование (клик), фильтр Стоимость (Платное), Тестировщик ПО (выбор из списка)

2. Каталог курсов, Программирование (клик), фильтр Скоро стартуют, Тестировщик ПО (выбор из списка)

3. Каталог курсов, Программирование (клик), фильтр Уровень (Нео), Тестировщик ПО (выбор из списка)

4. Каталог курсов, Программирование (клик), фильтр Вид обучения (Профессия), Тестировщик ПО (выбор из списка)

5. Каталог, Программирование (клик), фильтр - КОМБИНАЦИЯ ФИЛЬТРОВ, Тестировщик ПО (выбор из списка)

**Группа 3**

1. Каталог курсов, Программирование (наведение мышкой), Тестировщик ПО (выбор из списка)

**Группа 4**

1. Каталог, Полный Каталог, Тестировщик ПО (выбор из списка)

**Группа 5**

1. Каталог, Полный каталог, Поисковая строка, Тестировщик ПО (выбор из списка)

**Группа 6**

1. Каталог, Полный каталог, Поисковая строка, ввести Тестировщик ПО

**Группа 7**

1. Каталог, Полный Каталог, фильтр Скоро стартует, Тестировщик ПО (выбор из списка)

2. Каталог, Полный каталог, фильтр Направление (Программирование), Тестировщик ПО (выбор из списка)

3. Каталог, Полный каталог, фильтр Уровень (Нео), Тестировщик ПО (выбор из списка)

4. Каталог, Полный каталог, фильтр Вид обучения (Профессия), Тестировщик ПО (выбор из списка)

5. Каталог, Полный каталог, фильтр Стоимость (Платное), Тестировщик ПО (выбор из списка)

6. Каталог, Полный каталог, фильтр - КОМБИНАЦИЯ ФИЛЬТРОВ, Тестировщик ПО (выбор из списка)

**Группа 8 (временная)**

1. Каталог, Полный каталог, сверху Черная Пятница (Подробнее), Тестировщик ПО (выбор из списка)

**Группа 9**

1. Основная страница, Нео для начинающий (в кругу), фильтр Скоро стартует, Тестировщик ПО (выбор из списка)

2. Основная страница, Нео для начинающий (в кругу), фильтр Направление (Программирование), Тестировщик ПО (выбор из списка)

3. Основная страница, Нео для начинающий (в кругу), фильтр Вид обучения (Профессия), Тестировщик ПО (выбор из списка)

4. Основная страница, Нео для начинающий (в кругу), фильтр Стоимость (Платное), Тестировщик ПО (выбор из списка)

5. Основная страница, Нео для начинающий (в кругу), фильтр - КОМБИНАЦИЯ ФИЛЬТРОВ, Тестировщик ПО (выбор из списка)

**Группа 10**

1. Основная страница (раздел Изучайте актуальные темы), 
Программирование, Тестировщик ПО (выбор из списка)

(Примечание: сценарии с фильтрам не проверять) 

**Группа 11**

1. Основная страница (раздел Раскройте свои сильные стороны), Выбрать курс, Тестировщик ПО (выбор из списка)

**Группа 12**

1. Фут основной страницы, Каталог курсов, Тестировщик ПО (выбор из списка)

(Примечание: сценарии с фильтром не проверять)

**Группа 13**

2. Фут основной страницы, Программирование, Тестировщик ПО (выбор из списка)

(Примечание: сценарии с фильтром не проверять)

**Группа 14**

3. Фут основной страницы, О компании, Базовая страница с разделом “Источник знаний для роста в профессии”, Нео (освойте новую профессию), Тестировщик ПО (выбор из списка)

**Группа 15**

4. Фут основной страницы, О компании, Базовая страница с разделом “Постоянно открываем новые направления”, Программирование, Тестировщик ПО (выбор из списка)

**Группа 16 (временная)**

1. Основная страница, Черная пятница (Подробнее), Окно Черная Пятница, Выбрать курс, Тестировщик ПО (выбор из списка)

**ТЕСТИРОВАНИЕ СЦЕНАРИЕВ ПЕРЕХОДА ОТ СТРАНИЦЫ ПРОФЕССИИ “ТЕСТИРОВЩИК ПО” ФОРМЕ ЗАПИСИ НА КУРС**

ОР для данных сценариев: успешный переход к форме записи на курс.

1. Страница профессии, Записаться (вверху)

2. Блок “Черная пятница” в начале страницы профессии, Условия акции, Купить курс

3. Блок “Гарантия возврата денег” на странице профессии, Записаться

4. Блок “Черная пятница” в конце страницы профессии, Условия акции, Купить курс
 
**ТЕСТИРОВАНИЕ БЛОКА ЗАПИСИ НА ОБУЧЕНИЕ**

**А. Для незарегистрированных пользователей**

**Позитивные сценарии:**

1. Введение верного промокода

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле валидный промокод
- Нажать на кнопку "Применить"

ОР: изменение стоимости курса в соответствии с требованиями


2. Ручной ввод имени, телефона, маил для записи

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- В поле имя ввести валидное имя
- В поле телефон ввести валидный телефон
- В поле электронная почтка ввести валидную почту
- Нажать на кнопку "Записаться"

ОР: переход на страницу оплаты

3. Ручной ввод имени, телефона, маил для получения консультации

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- В поле имя ввести валидное имя
- В поле телефон ввести валидный телефон
- В поле электронная почтка ввести валидную почту
- Нажать на кнопку "Получить консультацию"

ОР: сообщение о скором звонке консультанта

4. Условия политики (наличие)

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "условия политики"

ОР: условия политики - visible

5. Условия пользовательского соглашения (наличие)

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "пользователькое соглашение"

ОР: условия пользовательсткого соглашения  - visible

6. Информация о количестве дней, которые остаются до старта курса?

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Провелить видимость информации (стартует через Х дней)
- Сопоставить количество дней с требованиями

ОР: количество дней соответсвует требованиям

7. Проверка стоимости курса (без скидки/со скидкой)

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о стоимости курса (без скидки/со скидкой)
- Сопоставить стоимости курса с требованиями

ОР: стоимость курса (без скидки/со скидкой) совпадает с требованиями

8. Проверка скидки в рублях

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме скидки 
- Сопоставить с требованиями

ОР: скидка соответсвует требованиям

9. Проверка суммы оплаты по месяцам

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме оплаты по месяцам
- Сопоставить с требованиями

ОР: сумма оплаты по месяцам соответсвует требованиям

10. Проверка дня окончания скидки

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о дне окончания скидки
- Сопоставить день с требованиями

ОР: день соответствует требованиям

11. Наличие блоков "возврат денег"/"сэкономьте еще 13%"/"есть вопросы?"

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость блоков "возврат денег"/"сэкономьте еще 13%"/"есть вопросы?

ОР: блоки возврат денег/сэкономьте еще 13%/есть вопросы - visible
 
 **Негативные сценарии:**

1. Введение неверного промокода

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле не валидный промокод
- Нажать на кнопку "Применить"

ОР: сообщение, что введен неверный промокод, стоимость курса не изменилась

2. Ввод невалидных данных (имя/телефон, маил) для записи на обучение

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- В поле имя ввести не валидное имя
- В поле телефон ввести не валидный телефон
- В поле электронная почтка ввести не валидную почту
- Нажать на кнопку "Записаться"

ОР: сообщение о неверно введенных данных, информация о правильном формате вводимых данных, отсутствие перехода на страницу оплаты

3. Ввод невалидных данных (имя/телефон, маил) для получения консультации

Precondition: осуществлен переход к блоку записи на обучение

Steps to repoduce:

- В поле имя ввести не валидное имя
- В поле телефон ввести не валидный телефон
- В поле электронная почтка ввести не валидную почту
- Нажать на кнопку "Получить консультацию"

ОР: сообщение о неверно введенных данных, информация о правильном формате вводимых данных, отсутствие соотбщения об ожидании звонка консультанта

**Б. Для зарегистрированных (не проходят обучения на других курсах)**

**Позитивные сценарии:**

1. Введение верного промокода 

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле валидный промокод
- Нажать на кнопку "Применить"

ОР: изменение стоимости курса в соответствии с требованиями

2. Автозаполнение полей имени и телефона для записи на обучение

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Поле имя заполнено валидным именем
- Поле телефон заполнено валидным телефоном
- Поле электронная почта заполнено валидной почтой
- Нажать на кнопку "Записаться"

ОР: все поля автоматически заполнены валидными данными, успешный переход на страницу оплаты

3. Автозаполнение полей имени и телефона для получения консультации

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Поле имя заполнено валидным именем
- Поле телефон заполнено валидный телефоном
- Поле электронная почта заполнено валидной почтой
- Нажать на кнопку "Получить консультацию"

ОР: все поля автоматически заполнены валидными данными, сообщение о скором звонке консультанта

4. Условия политики (наличие)

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "условия политики"

ОР: условия политики - visible

5. Условия пользовательского соглашения (наличие)

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "условия пользовательского соглашения"

ОР: условия пользовательского соглашения - visible

6. Информация о количестве дней до старта курса?

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Провелить видимость информации (стартует через Х дней)
- Сопоставить количество дней с требованиями

ОР: количество дней соответсвует требованиям

7. Проверка стоимости курса (без скидки/со скидкой)

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверка видимости стоимости курса (без скидки/со скидкой) 
- Сопоставить стоимость с требованиями

ОР: стоимость курса (без скидки/со скидкой) соответсвует требованиям

8. Проверка скидки в рублях

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме скидки в рублях
- Сопоставить с требованиями

ОР: скидка в рублях соответсвует требованиям

9. Проверка суммы оплаты по месяцам

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме оплаты по месяцам
- Сопоставить сумму оплаты по месяцам с требованиями

ОР: сумма оплаты по месяцам соответствует требованиям

10. Проверка дня окончания скидки

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о дне окончания скидки
- Сопоставить с требованиями

ОР: дата окончания скидки соответсвует требованиям

11. Наличие блоков возврат денег/сэкономьте еще 13%/есть вопросы?

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость блоков "возврат денег"/"сэкономьте еще 13%"/"есть вопросы?

ОР: блоков возврат денег/сэкономьте еще 13%/есть вопросы - visible

**Негативные сценарии:**

1. Введение неверного промокода

Precondition: вход в личный кабинет, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле не валидный промокод
- Нажать на кнопку "Применить"

ОР: сообщение, что введен неверный промокод, стоимость курса не изменилась

**В. Для зарегистрированных (проходят обучения на других курсах)**

**Позитивные сценарии:**

1. Введение верного промокода 

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле валидный промокод
- Нажать на кнопку "Применить"

ОР: изменение стоимости курса в соответствии с требованиями

2. Автозаполнение полей имени и телефона для записи на обучение

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Поле имя заполнено валидным именем
- Поле телефон заполнено валидный телефоном
- Поле электронная почта заполнено валидной почтой
- Нажать на кнопку "Записаться"

ОР: все поля автоматически заполнены валидными данными, успешный переход на страницу оплаты

3. Автозаполнение полей имени и телефона для получения консультации

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Поле имя заполнено валидным именем
- Поле телефон заполнено валидный телефоном
- Поле электронная почта заполнено валидной почтой
- Нажать на кнопку "Получить консультацию"

ОР: все поля автоматически заполнены валидными данными, сообщение о скором звонке консультанта

4. Условия политики (наличие)

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "условия политики"

ОР: условия политики - visible

5. Условия пользовательского соглашения (наличие)

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость ссылки "пользовательского соглашения"

ОР: пользовательское соглашение - visible

6. Информация о количестве дней до старта курса

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверка видимости количества дней до старта
- Сопоставить количество дней с требованиями

ОР: количество дней совпадает с требованиями

7. Проверка стоимости курса (без скидки/со скидкой)

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость стоимости курса (без скидки/со скидкой)
- Сопоставить стоимость курса с требованиями

ОР: стоимость курса совпадает с требованиями

8. Проверка скидки в рублях

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме скидки в рублях
- Сопоставить скидку с требованиями

ОР: скидка в рублях совпадает с требованиями

9. Проверка суммы оплаты по месяцам

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о сумме оплаты по месяцам
- Сопоставить сумму оплаты по месяцам с требованиями

ОР: сумма совпадает с требованиями

10. Проверка дня окончания скидки

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость информации о дне окончания скидки
- Сопоставить с требованиями

ОР: день окончания скидки совпадает с требованиями

11. Наличие блоков возврат денег/сэкономьте еще 13%/есть вопросы?

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Проверить видимость блоков "возврат денег"/"сэкономьте еще 13%"/"есть вопросы?

ОР: блоки возврата денег/сэкономьте еще 13%/есть вопросы - visible

**Негативные сценарии:**

1. Введение неверного промокода

Precondition: вход в личный кабинет, предварительно оплачен другой курс обучения, осуществлен переход к блоку записи на обучение

Steps to repoduce:

- Нажать "У меня есть промокод"
- Ввести в появившееся поле не валидный промокод
- Нажать на кнопку "Применить"

ОР: сообщение, что введен неверный промокод, стоимость курса не изменилась

**ТЕСТИРОВАНИЕ ИНТЕГРАЦИИ С БАЗОЙ ДАННЫХ**

**Позитивные сценарии:**

1. Появление в БД (записавшиеся на курс) нового ранее незарегистрированного пользователя 

2. Появление в БД (записавшиеся на курс) ранее зарегистрированного пользователя 

3. Появление в БД (ожидающих звонок) ранее незарегистрированного пользователя

4. Появление в БД (ожидающих звонок) ранее незарегистрированного пользователя

## **Перечень используемых инструментов с обоснованием выбора**

**Gradle** (наиболее современный фреймворк, более простая интеграция с другими инструментами)

**JUnit5** (наиболее современная библиотека тестирования)

**Selenide** (удобство для тестирования в разных браузерах, упрощенный синтаксис, более простая работа с селекторами - поиск по тексту)

**Lombok** (позволяет при помощи аннотаций составлять конструкторы, геттеры и сеттеры)

**Docker** для быстрой загрузки и развертывания контейнера с MySQL 

**MySQL** (более простое использование)

**Allure** для составления отчетов (более наглядно и систематизировано представлены результаты тестирования)

**Appveyor** для CI (простая интеграция с GItHub, конфигурации хранятся в виде yml файлов

## **Перечень необходимых разрешений/данных/доступов**

1. Тестовый режим сервиса (желательно)

2. Предоставление разрешения к БД

3. Подготовка аккаунтов с ФИО, номером телефона и mail

4. Перечень и описание возможных рисков при автоматизации

5. Риск падения тестов при появлении новых и исчезновении старых сценариев перехода в профессию Тестировщик ПО в связи с сезонными скидками и дополнительными акциями (частое изменение структуры страницы).

6. Множество путей перехода в профессию сопряжено с риском того, что некоторые теги будут идентичные.

## **Перечень необходимых специалистов для автоматизации**

Инженер по автоматизации тестирования - 1

## **Интервальная оценка с учётом рисков (в часах)**

Подготовка мануальных тестов (40 часов)

Автоматизация мануальных тестов (75 часов)

Проведение тестирования (4 часа)

Формирование отчета о тестировании (3 часа)
