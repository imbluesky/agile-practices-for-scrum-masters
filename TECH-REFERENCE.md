# Справочник технологий и практик

## Фреймворки
Набор готового функционала от сторонних разработчиков в виде модулей или библиотек, готовый для переиспользования в разных проектах.
В отличие от библиотек, которые входят в часть программы, фреймворк вызывает код разработчика.
Аналогия: фреймворк - квартира, библиотека - это стол (его можно переиспользовать).

Примеры фреймворков:
JAVA - Spring
Python - Django
JavaScript - Vue.js, Angular, React

Примеры библиотек:
WinApi - библиотека вызова системных функций на уровне ОС
math.cpp - библиотека математических функций для C++ 

## Типовая архитектура

FrontEnd: JavaScript, Angular, React, Vue
BackEnd: Java

Форматы обмена данных: XML, JSON, Binary

## Logical structure
Layers:
controller 'отвечает за выбор метода,журнолирование,безопастность. Отвечает на вопрос: сюда ли ты пришел?
service    'компоненты,которые несут бизнес логику, по факту = user story
domain     'объекты, которые моделируют предметную область. Наш класс
dao        '= репозиторий.Это класс,который содержит внутри себя логику работы с БД
