# Отчёт о тестировании Внедрения доп. бонуса новым клиентам.

## Краткое описание

08.07.21 - 08.07.21 было проведено функциональное тестирование приложения Внедрение доп. бонуса новым клиентам.

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* [Регулярный бонус 0,3 со спец бонусом 0,6 в сумме не дают 0,9](https://github.com/VladimirAlf/Precision/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Код](https://github.com/VladimirAlf/Precision/commit/edbfb942b357133919b81ef2e8ffae59079a4afa#diff-1597d2955516e4d404c9395c883d26475c58b27032926237f062392226c69fe9)


В качестве тестовых данных использовались данные взяты из [кода](https://github.com/VladimirAlf/Precision/commit/edbfb942b357133919b81ef2e8ffae59079a4afa#diff-1597d2955516e4d404c9395c883d26475c58b27032926237f062392226c69fe9):
* regular bonus = 0,3 и special bonus = 0,6 в сумме дают 0,9

Тестирование производилось в следующем окружении:
* Windows 10 Home, 64-разрядная ОС
* OpenJDK11U-jdk_x64_windows_hotspot_11.0.11_9
* Intellij IDEA Community Edition 2021.1.3
