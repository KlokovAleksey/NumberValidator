# Отчёт о тестировании приложения Credit Card Number Validator.

## Краткое описание

06.11.2020 было проведено функциональное,white box тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Ошибка валидации 14 значного номера карты](https://github.com/KlokovAleksey/NumberValidator/issues/1)
* [Ошибка валидации 15 значного номера карты](https://github.com/KlokovAleksey/NumberValidator/issues/2)
* [Ошибка валидации 19 значного номера карты](https://github.com/KlokovAleksey/NumberValidator/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [ Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Генератор И Валидатор Номеров Кредитных Карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [Credit Card Number Validator](https://github.com/KlokovAleksey/NumberValidator/blob/master/src/Main.java)

В качестве тестовых данных использовались данные c сайта [freeformatter.com](https://github.com/KlokovAleksey/NumberValidator/blob/master/src/Main.java): 
1. VISA:
* 4929717403925943
* 4485461756829156
* 4539385619259504848
* Ожидаемый результат: **OK**
2. MasterCard:
* 5533890649595203
* 5591613766607125
* 2221000354501362
* Ожидаемый результат: **OK**
3. American Express (AMEX):
* 342303159591648
* 347689085444026
* 349789492456338
* Ожидаемый результат: **OK**
4. Discover:
* 6011116223454651
* 6011241803609803
* 6011371775998287253
* Ожидаемый результат: **OK**
5. JCB:
* 3528004408504693
* 3534405898235742
* 3540656519981451931
* Ожидаемый результат: **OK**
6. Diners Club - North America:
* 5473213109260733
* 5409891307493542
* 5434445683067740
* Ожидаемый результат: **OK**
7. Diners Club - Carte Blanche:
* 30373826818580
* 30010820645466
* 30529232963654
* Ожидаемый результат: **OK**
8. Diners Club - International:
* 36813093647950
* 36410686775635
* 36170911700093
* Ожидаемый результат: **OK**
9. Maestro:
* 6762057715010653
* 6304769962085882
* 6759505450593627
* Ожидаемый результат: **OK**
10. Visa Electron:
* 4913916454397949
* 4508159737321128
* 4917627535556629
* Ожидаемый результат: **OK**
11. InstaPayment:
* 6397055257646036
* 6385641832598414
* 6373899761404293
* Ожидаемый результат: **OK**

Тестирование производилось в следующем окружении:
* Windows Embedded 8.1 Industry Pro x64
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+))) 11, смешанный режим)
* InteleJ IDEA Community 2020.2.3
