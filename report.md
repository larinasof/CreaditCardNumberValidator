# Отчёт о тестировании установки IntelliJ IDEA и функциональности валидации номера банковской карты

## Краткое описание
10.06.2020 было проведена установка IntelliJ IDEA и функциональное тестирование валидации номера банковской карты.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:

* https://github.com/larinasof/CreaditCardNumberValidator/issues/1
* https://github.com/larinasof/CreaditCardNumberValidator/issues/2
* https://github.com/larinasof/CreaditCardNumberValidator/issues/3
* https://github.com/larinasof/CreaditCardNumberValidator/issues/4
* https://github.com/larinasof/CreaditCardNumberValidator/issues/5
* https://github.com/larinasof/CreaditCardNumberValidator/issues/6

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

* Руководство по установке IntelliJ IDEA
* Программа IntelliJ IDEA
* Java-код для тестирования функциональности валидации номера банковской карты

В качестве тестовых данных для установки IntelliJ IDEA использовалось руководство по установке.
Ожидаемый результат:IntelliJ IDEA устанавливается и работает согласно руководству.

В качестве тестовых данных для тестирования функциональности валидации номера банковской карты использовались данные генератора валидных номеров банковских карт https://www.freeformatter.com/credit-card-number-generator-validator.html
* перечень валидных номеров:
    * 4024007144953477 (VISA)
    * 4024007117870218808 (VISA)
    * 6011276762965606 (Discover)
    * 6011177048798799018 (Discover)
    * 30435608971950 (Diners Club - Carte Blanche)
    * 4026961662045058 (Visa Electron)
    * 5274300574636975 (Master Card)
    * 3537596026323470 (JCB)
    * 3528572584817732884 (JCB)
    * 36056304931132 (Diners Club - International)
    * 6379483830529374 (InstaPayment)
    * 370587349992642 (American Express)
    * 5534449183072035 (Diners Club - North America)
    * 6761994676102973 (Maestro)

Ожидаемый результат: результат вывода программы "Result is OK".
  
Тестирование производилось в следующем окружении:

* ОС Windows 10 версия 1903 ×64
* OpenJDK version "11.0.7"