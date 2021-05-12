# Отчёт о тестировании Money Transfer

## Краткое описание

12.05.21 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Неправильное отображение суммы баланса если сумма баланса превышает 2_147_483_647.](https://github.com/Masikoshka/DZ_1.2_Money_Transfer/issues/1#issue-890372858)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Код разработчика.](https://github.com/Masikoshka/DZ_1.2_Money_Transfer/blob/master/src/Main.java)
* [Чек-лист.](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)

В качестве тестовых данных использовались:
* [Информация об ошибке от клиента.](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)
* [Граничные значения типа `int`.](https://ru.wikibooks.org/wiki/Java/%D0%A2%D0%B8%D0%BF%D1%8B_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)


Тестирование производилось в следующем окружении:
* Windows 10, версия: 20H2, разрядность 64.
* Версия Java: 11.
