# **Домашнее задание к занятию "Базы данных"**-***Вуколов Евгений***

## **Задание 1**

 Таблица №1 Сотрудники (

идентификатор, первичный ключ, serial

Фамилия  varchar(20) NOT NULL,

Имя      varchar(20) NOT NULL,

Отчество varchar(20) NOT NULL,

идентификатор структурного подразделения, внешний ключ, integer )


 Таблица №1 Оклад (

идентификатор сотрудника varchar(20)
 
размер оклада mediumint
 
идентификатор проекта на который назначен, внешний ключ, integer )


 Таблица №1 Должность (

идентификатор сотрудника, внешний ключ, integer

название должности varchar (50) NOT NULL )


 Таблица №1 Тип подразделения (

Отдел varchar(30) NOT NULL,

Группа varchar(30) NOT NULL,

Департамент varchar(30) NOT NULL,

идентификатор структурного подразделения, внешний ключ, integer )


 Таблица №1 Структурное подразделение (

идентификатор, первичный ключ, integer

Название структуктурного подразделения varchar(50) NOT NULL,
)

 Таблица №1 Date (

идентификатор сотрудника, внешний ключ, integer

Дата найма, date )


 Таблица №1 Адрес филиала (

Адрес филиала varchar(50) NOT NULL,

идентификатор структурного подразделения, внешний ключ, integer )

 Таблица №1 Проект на который назначен (

Первичный ключ, integer
 
Название проекта varchar(30)

идентификатор сотрудника, внешний ключ, integer )





 
