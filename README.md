# План автоматизации тестирования функции записи на обучение по программе "Тестировщик ПО" на веб-сайте Нетология

## Перечень автоматизируемых сценариев. ##

### Сценарии перехода на страницу с формой записи на курс "Тестировщик ПО". ###

**Сценарий №1**

Предусловие: 

Пользователь неавторизован/авторизован

1. Открыть главную страницу [Нетология](https://netology.ru/)
2. Выбрать направление обучения "Программирование"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/5657b9c8-31e3-4c28-8d95-4ee45f16bfc8)

3. Из списка курсов выбрать "Тестировщик ПО"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/40dae445-a92b-4806-b2cf-2556789997ef)

4.  На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/81760d57-349a-4137-80d9-d9b09c3c0093)

**Сценарий №2**   

Предусловие: 

Пользователь неавторизован/авторизован

1. Открыть главную страницу [Нетология](https://netology.ru/)
2. Нажать кнопку "Каталог курсов"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/2a7b47ba-43dd-44a6-88a2-5767efca835e)

3. Выбрать из списка "Программирование"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/1f499548-5bb7-4917-bcde-eac171755c8a)

4. На открывшейся странице [Программирование](https://netology.ru/development) выбрать "Тестировщик ПО"
5. На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"

**Сценарий №3**

Предусловие: 

Пользователь неавторизован/авторизован

1. Проскролить до футера на главной странице [Нетология](https://netology.ru/)
2. Нажать кнопку "Каталог курсов"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/720c6d77-969c-4981-8846-aa6164bb15fe)

3. На открывшейся странице [Каталога курсов](https://netology.ru/navigation) выбрать "Тестировщик ПО"
4.  На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/81760d57-349a-4137-80d9-d9b09c3c0093)

**Сценарий №4**

Предусловие: 

Пользователь неавторизован

1. Проскролить до футера на главной странице [Нетология](https://netology.ru/)
2. Нажать кнопку "Программирование"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/26fb4ed6-afb1-4156-ad12-e6df7d7bd932)
3. На открывшейся странице [Программирование](https://netology.ru/development) выбрать "Тестировщик ПО"
4. На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"

**Сценарий №5**

Предусловие: 

Пользователь неавторизован/авторизован

1. Открыть главную страницу [Нетология](https://netology.ru/)
2. Нажать кнопку "Каталог курсов"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/2a7b47ba-43dd-44a6-88a2-5767efca835e)

3. В поисковой строке "Какой курс вам нужен?" ввести "Тестировщик ПО"
4. Из выпадающего списка выбрать опцию "Тестировщик ПО"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/7931f308-cfa0-4422-bd4f-61dc74659424)

5. На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"

**Сценарий №6**

Предусловие: 

Пользователь неавторизован/авторизован
Открыта страница  [Каталога курсов](https://netology.ru/navigation) выбрать "Тестировщик ПО"

1. В фильтрах в разделе "Навыки" выбрать "Тестирование ПО"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/ca65cba8-3422-4378-8417-66868f859de1)

2. Из списка выбрать курс "Тестировщик ПО"
![image](https://github.com/esaukova/AQA_plan_ESaukova/assets/81514189/1e14012a-f8bd-49da-a64c-ecf8e1a10e6d)

3. На открывшейся странице [курса "Тестировщик ПО"](https://netology.ru/programs/qa) кликнуть на кнопку "Записаться"

### Сценарии заполнения формы записи на курс "Тестировщик ПО". ###

**Позитивные сценарии**
| Идентификационный  номер | Название | Шаги | Ожидаемый результат|
|----------|----------|----------|-----------|
| ТС 1     | Ввод валидных данных в [поле записи](https://netology.ru/programs/qa#/order)   |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи успешно отправлена. Получено сообщение об успешной записи на курс|
|          |                                                                                |2.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)   ||
|          |                                                                                |3.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)  ||
|          |                                                                                |4.Нажать кнопку "Записаться" ||                                                                                               
        
**Негативные сценарии**	
			
| Идентификационный  номер | Название | Шаги | Ожидаемый результат|
|----------|----------|----------|-----------|
| ТС 2     | Ввод цифр в поле "Имя"           |1.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)|Форма записи не отправляется. Под полем "Имя" появляется сообщение "Имя должно состоять из букв"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)   ||
|          |                                                                                |3.Ввести цифры в поле "Имя". Например: 1234||
|          |                                                                                |4.Нажать кнопку "Записаться" ||   
|          |                                               |                                |                             ||
| ТС 3     | Ввод спец.символов в поле "Имя"           |1.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)|Форма записи не отправляется. Под полем "Имя" появляется сообщение "Недопустимые символы. Имя должно состоять из букв"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)   ||
|          |                                                                                |3.Ввести спец.символы в поле "Имя". Например: (&!-%)||
|          |                                                                                |4.Нажать кнопку "Записаться" ||   
|          |                                               |                                |                             ||
| ТС 4     | Ввод одной буквы в поле "Имя"           |1.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99) |Форма записи не отправляется. Под полем "Имя" появляется сообщение "Имя должно содержать минимум 2 буквы"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)  ||
|          |                                                                                |3.Ввести одну букву в поле "Имя"||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 5     | Отправка формы с пустым полем "Имя"           |1.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99) |Форма записи не отправляется. Под полем "Имя" появляется сообщение "Обязательное поле"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)  ||
|          |                                                                                |3.Оставить поле "Имя" незаполненным||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 6     | Ввод в поле "Телефон" 10 цифр           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи не отправляется. Под полем "Телефон" появляется сообщение "Номер в формате +7 (999) 999-99-99"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)   ||
|          |                                                                                |3.Ввести в поле "Телефон" 10 цифр. Например: +7 960 066-20-3||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 7     | Ввод в поле "Телефон" 12 цифр           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи не отправляется. Под полем "Телефон" появляется сообщение "Номер в формате +7 (999) 999-99-99"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)   ||
|          |                                                                                |3.Ввести в поле "Телефон" 12 цифр. Например: +7960 066-20-333||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 8     | Отправка формы с пустым полем "Телефон"           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария)  |Форма записи не отправляется. Под полем "Телефон" появляется сообщение "Обязательное поле"|
|          |                                                                                |2.Ввести валидные данные в поле "Электронная почта" (латиница, символ @, имя почтового сервера. Например: bubu@gmail.com)  ||
|          |                                                                                |3.Оставить поле "Телефон" незаполненным||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 9     | Ввод в поле "Электронная почта" почту на кириллице           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи не отправляется. Под полем "Электронная почта" появляется сообщение "Неверный email. Адрес электронной почты заполняется на латинице"|
|          |                                                                                |2.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)    ||
|          |                                                                                |3.Ввести в поле "Электронная почта" почту на кириллице. Например: катя@gmail.com ||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 10     | Ввод в поле "Электронная почта" почту без @           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи не отправляется. Под полем "Электронная почта" появляется сообщение "Неверный email. Пропущен @"|
|          |                                                                                |2.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)    ||
|          |                                                                                |3.Ввести в поле "Электронная почта" почту без @ . Например: katyagmail.com ||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 11     | Ввод в поле "Электронная почта" почту без имени почтового сервера           |1.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария) |Форма записи не отправляется. Под полем "Электронная почта" появляется сообщение "Неверный email. Укажите имя почтового сервера"|
|          |                                                                                |2.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99)    ||
|          |                                                                                |3.Ввести в поле "Электронная почта" почту без имени почтового сервера. Например: katya@.com ||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
|          |                                               |                                |                             ||
| ТС 12     | Отправка формы с пустым полем "Электронная почта"           |1.Ввести валидные данные в поле «Телефон»(11 цифр в формате +7 (999) 999-99-99) |Форма записи не отправляется. Под полем "Электронная почта" появляется сообщение "Обязательное поле"|
|          |                                                                                |2.Ввести валидные данные в поле «Имя» (латиница, кириллица, пробел, тире, минимум две буквы. Например: Анна-Мария)||
|          |                                                                                |3.Оставить поле "Электронная почта" незаполненным||
|          |                                                                                |4.Нажать кнопку "Записаться" || 
     
### Сценарии тестирования API и ответов от BD. ###

| Идентификационный  номер | Название | Шаги | Ожидаемый результат|
|----------|----------|----------|-----------|
| ТС 13     | POST request с валидными данными           |1.Отправить POST запрос на эндпоинт URL/users с валидными данными в формате |Статус-код ответа должен быть 200. В теле ответа должны содержаться данные пользователя,соответствующие отправленным тестовым данным.|
|          |                                             | { ||                        
|          |                                                                                |"username": "vasya",||
|          |                                                                                |"phone": "+79605555555", || 
|          |                                                                               | "email": "bubu@gmail.com"||
|          |                                            |   } ||  
|          |                                               |                                |                             ||            
| ТС 14     | POST request с данными пользователя, который уже отправил форму записи на курс          |1.Отправить POST запрос на эндпоинт URL/users с валидными данными существующего пользователя в формате |Статус-код ответа должен быть 409. Конфликт данных |
|          |                                                                                |{ || 
|          |                                                                                |"username": "vasya",||
|          |                                                                                |"phone": "+79605555555", || 
|          |                                                                               | "email": "bubu@gmail.com"  ||
|          |                                            |   } ||  
|          |                                               |                                |                             ||   
| ТС 15     | POST request с невалидными данными          |1.Отправить POST запрос на эндпоинт URL/users с невалидными данными в формате |Статус-код ответа должен быть 400. Запрос содержит невалидные данные|
|          |                                                                                |{ || 
|          |                                                                                |"username": "123",||
|          |                                                                                |"phone": "abc", || 
|          |                                                                               | "email": "bubu"   |
|          |                                            |   } ||  


## Перечень используемых инструментов с обоснованием выбора. ##

 **1. Среда разработки - IntelliJ IDEA** ведущая IDE для разработки на Java. Помогает работать продуктивнее за счет интеллектуальной помощи в написании кода, надежных рефакторингов, быстрой навигации по коду, широкого набора встроенных инструментов разработчика, поддержки веб- и корпоративной разработки и многих других полезных возможностей.
 
 **2. Язык программирования: Java 11**
 
 **3. Cистема для автоматизации сборки: Gradle** Подробный и хорошо продуманный программный интерфейс упрощает отслеживание и настройку конфигурации сборки, контроль ее исполнения.
 
 **4. Фреймворк для модульного тестирования: JUnit 5**  мощное и гибкое обновление фреймворка JUnit, которое предоставляет множество улучшений и новых функций для написания тестов.
 
 **5. Фреймворк для автоматизации тестирования: Selenide** это фреймворк для автоматизированного тестирования веб-приложений на основе Selenium WebDriver, дающий следующие преимущества:
Изящный API, Стабильные тесты, Мощные селекторы, Простая конфигурация
 
 **6. Набор средств веб-разработки: DevTools**
 
 **7. Библиотеки: Lombok** (основанная на аннотациях библиотека Java, позволяющая сократить шаблонный код), **Faker**(библиотека, которая позволяет генерировать тестовые данные.), **Rest Assured**(библиотека для тестирования API. Она умеет делать две вещи: посылать запросы и проверять ответы.)
 
 **8. Система контроля версии: GIT** применяется для управления версиями и интегрирована со средой разработки
 
 **9. Система CI/CD: Jenkins** Программная система с открытым исходным кодом на Java, предназначенная для обеспечения процесса непрерывной интеграции программного обеспечения.
 
 **10. Система репортинга: Allure** инструмент для создания отчетов о результатах тестирования в автоматизированных тестовых сценариях. Он предоставляет красиво оформленные и интерактивные отчеты, которые позволяют легко анализировать результаты тестирования и принимать информированные решения на основе полученных данных.


## Перечень необходимых разрешений, данных и доступов. ##
1. Разрешение на автоматизацию тестирования функции записи на курс "Тестировщик ПО"
2. Доступ к тестовому окружению, тестовой базе данных
3. Технические требования к форме записи
4. Данные аналитиков по поведению пользователей на сайте Нетология

## Перечень и описание возможных рисков при автоматизации. ##
1. Нагрузка на сервер. Риск вызова сбоев или отказов в работе сервера.
2. Изменения в пользовательском интерфейсе могут привести к нарушению сценариев автоматизации.
3. Трудности при поиске и привязке тестов посредством локаторов элементов на веб-страницах. 


## Перечень необходимых специалистов для автоматизации. ##
AQA Engineer Junior

## Интервальная оценка с учётом рисков в часах. ##
20-30 часов
