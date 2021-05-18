# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

18.05.2021 - 19.05.2021 было проведено функциональное тестирование приложения и тестирование граничных значений

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* [Максимальное количество символов при вводе номера карты ограничено 16](https://github.com/freed1994/JavaFirst/issues/1)
* [Минимальное количество символов при вводе номера карты ограничено 16](https://github.com/freed1994/JavaFirst/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Гениратор валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)


В качестве тестовых данных использовались данные [С гениратора валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* VISA: 4533083569119344, 4532189588768770
* Discover: 6011962806865569, 6011692005515919
* MasterCard: 5553322823259567, 5225600986030844
* JCB: 3529496959396595, 3528771281195159

Тестирование производилось в следующем окружении:
* Windows 10 Pro 64-bit
* openjdk version "11.0.10"
* IntelliJ IDEA 2021.1.1 (Community Edition)
