# Тестовое задание "ЖКХ"

## Документация
Решение состоит из двух проектов: HousingCommunalServicesTestTask и HousingCommunalServicesClassLibrary.

>______________________________________________

## HousingCommunalServicesTestTask
Основной проект, из которого происходит запуск приложения, также в его корневой директории лежит файл **Config.xml**.

>______________________________________________

## HousingCommunalServicesClassLibrary
Дополнительный проект, в котором размещен функционал приложения, разделение нужно чтобы этот модуль, в случае необходимости, мог переиспользоваться.
Включает в себя следующие компоненты: 

* **XML**
* **Report**
* **Manager**
* **GoogleAPI**

>______________________________________________

## XML

**User** >>> Структура для цельного представления данных, полученных из файла конфигурации.

**XMLReader** >>> Статический класс, который считывает информацию с помощью метода **Read** из файла конфигурации.

>______________________________________________

## Report

**IReport** >>> Интерфейс, который реализуют классы отвечающие за вывод информации.

**ConsoleReport** >>> Класс, отвечающий за вывод информации в консольном приложении.

>______________________________________________

## Manager
**HousingCommunalServicesManager** >>> Класс, отвечающий за получение информации от базы данных.

>______________________________________________

## GoogleAPI
**GoogleAPIAccountManager** >>> Класс, для взаимодействия с гугл аккаунтом.
