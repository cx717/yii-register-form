# Тестовое задание для TR Logic LLC компании

## Задача

Реализовать, небольшое веб-приложение отображающее форму входа/регистрации нового пользователя. Продумайте самостоятельно необходимые поля.

В результате заполнения формы пользователь должен предоставить информацию о себе, которая запишется в БД. После входа должен отображаться профайл зарегистрировавшегося пользователя.

Используемые технологии/фреймворки/СУБД — на Ваше усмотрение.

- Форма должна быть выполнена способом, понятным пользователю, содержать необходимые инструкции, комментарии и т.п. (usability).
- Исходный код должен содержать средства верификации и валидации полей, а также защиту от некорректного ввода данных, спецсимволов, попыток взлома и т.п.
- Структура базы данных должна быть обоснованной.
- Вспомогательные тексты в форме (названия полей, подсказки, ошибки и пр.) должны быть сформулированы грамотно и понятно пользователю, выдержан деловой и уважительный стиль обращения.
- Код должен быть написан понятно и аккуратно, с соблюдением табуляции и прочих элементов написания, без лишних элементов и функций, не имеющих отношения к функционалу тестового задания, снабжен понятными комментариями (документацией).
- Обращаем внимание на то, что имеет значение не только техническая часть выполненного задания (коды), но и дизайнерская (внешний вид, логика оформления, полнота инструкций).
- Пожалуйста, выполняя тестовое задание, обратите особое внимание на качество и безопасность кода.

Особое внимание стоит обратить на следующие моменты:
- Читабельность и наличие элементарной архитектуры, ООП приветствуется (задание где весь код в одном файле будет сразу отклонено).
- Чистота и оформление кода не менее важный фактор, код должен быть написан в едином стиле (желательно в рекомендуемом для конкретного языка). 
- К чистоте относятся отсутствие копипаста и дублирования логики.
- Отсутствие явных уязвимостей (например, SQL-инъекций).

Отсутствие или нарушение данных пунктов вероятнее всего послужит причиной отказа.

Будет плюсом:
- Оптимизация базы данных (индексация полей и т.п.).
- Использование фреймворка для Front-End-части приложения.

Тестовое задание должно быть представлено в следующем виде:
- Ссылка на публичный репозиторий (GitHub, BitBucket, GitLab) с исходным кодом.
- Ссылка на сайт для тестирования функционала. Или Dockerfile и docker-compose.yaml, позволяющие развернуть локально командой docker-compose up работоспособную копию сайта.

## Реализация

* Данное приложение реализовано на фреймворке Yii2-basic.
* В качестве системы управления базой данных была выбрана система MySQL.
* В качестве frontend  фреймворка выступает bootstrap.

## Ссылка на Демо версию

[демо](http://soundsurfers.ru/)

## Наиболее важные файлы, участвующие в реализции функционала приложения

( в каждом из этих файлов есть коментарии, позволяющие понять для чего именно предназначен этот файл )

* controllers/SiteController.php

* migrations/m190122_153844_create_user_table.php

* models/LoginForm.php    
* models/RegistrationForm.php
* models/User.php   

* views/layout/main.php

* views/site/error.php
* views/site/index.php
* views/site/login.php
* views/site/profile.php
