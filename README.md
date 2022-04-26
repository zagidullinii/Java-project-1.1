# **Отчёт о тестировании пополнение баланса** 
## При пополнений баланса произошла ошибка 
###### 05.04.2022 10.55 -05.04.2022 11.10 было проведено функциональное тестирование пополнения баланса.
На тестирование затрачено 00 часов 15 мин.
В результате тестирования выявлены следующие дефекты:
- [эмитация ошибки пополнения счета](https://github.com/zagidullinii/Java-project-1.1/issues/1#issue-1112647542)
## Описание процесса тестирования
###### В процессе тестирования использовались следующие артефакты:
- отчет о тестирований
###### В качестве тестовых данных использовались данные:
- int Balans = 2_000_000_000;
- int replenishment = 500_000_000;
- int total = Balans + replenishment;
- System.out.println(total);
- мы получаем значение -1794967296
- должны получить значение 2 500 000 000
###### Тестирование производилось в следующем окружении:
- Windows 10 Корпоративная, 64-разрядная операционная система
- java.exe 11 версия
- IDEA Community Edition
