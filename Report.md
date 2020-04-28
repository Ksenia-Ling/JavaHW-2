# Отчёт о тестировании приложения Credit Card Number Validator

## Краткое описание

28.04.20 было проведено функциональное тестирование приложения Credit Card Number Validator

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* [При проверке валидной карты из 19 символов Validator выдаёт Fail](https://github.com/Ksenia-Ling/JavaHW-2/issues/1) 


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Руководство по установке IntelliJ IDEA
* Баг-репорт
* Отчёт о тестировании


В качестве тестовых данных использовались данные из [генератора валидных карт:](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers)

* 5154427029843610 master card
* 6011253016983461 discover
* 4582311602724774 visa
* 5018567754509419 maestro
* 4024007190850872100 visa


Ожидаемый результат:

При запуске проверки вывод в IntelliJ IDEA строк
```
Result is OK

Process finished with exit code 0
```

Тестирование производилось в следующем окружении:
* ОС: Windows 10 pro x64
* openjdk version "11.0.7" 2020-04-14
* IntelliJ IDEA 2020.1 (Community Edition)