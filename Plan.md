Перечень автоматизируемых сценариев:


Валидные данные:

Поле “Имя” - Ввод на русском языке, допустим ввод тире, не допустимы цифры, спецсимволы, максимальная длина 30 символов; (Например, Иван)

Поле “Фамилия” - Ввод на русском языке, допустим ввод тире, не допустимы цифры, спецсимволы, максимальная длина 30 символов; (Например, Иванов)


Поле “Телефон” - +7 далее 10 цифр, не допустим ввод букв, спецсимволов. (Например, +7 9555000214);

Поле “Паспорт” - 10 цифр; не допустим ввод букв, спецсимволов. (Например, 25 00 142142)


#1 Покупка тура по дебетовой карте при вводе валидных данных

Шаги:

* открыть форму покупки тура
* кликнуть кнопку “купить”
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Фамилия” валидные данные
* ввести в поле “Телефон” валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Заявка успешно отправлена. В ближайшее время с Вами свяжется оператор”


#2 Отправка формы заявки на покупку тура при вводе невалидных данных в поле “Имя”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” невалидными данными
* ввести в поле “Телефон” валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте данные в поле “Имя”


#3 Отправка формы заявки на покупку тура при вводе невалидных данных в поле “Фамилия”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить”
* в открытой форме заполнить поле “Фамилия” невалидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте данные в поле “Фамилия”


#4 Отправка формы заявки на покупку тура при вводе невалидных данных в поле “Телефон”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” невалидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте данные в поле “И””


#5 Покупка тура в кредит при вводе валидных данных

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” валидные данные
* ввести в поле “Паспорт” ввести валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Заявка успешно отправлена. После подтверждения выдачи кредита с Вами свяжется оператор”


#6 Отправка формы на покупку тура в кредит при вводе невалидных данных поле “Фамилия”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” невалидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” валидные данные
* ввести в поле “Паспорт” ввести валидные данные
* кликнуть кнопку “Отправить заявку”

* Ожидаемый результат: переход на страницу с сообщением “Проверьте поле “Фамилия””

#7 Отправка формы на покупку тура в кредит при вводе невалидных данных поле “Имя”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” невалидными данными
* ввести в поле “Телефон” валидные данные
* ввести в поле “Паспорт” ввести валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте поле “Имя””


#8 Отправка формы на покупку тура в кредит при вводе невалидных данных поле “Телефон”

Шаги:
* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон”невалидные данные
* ввести в поле “Паспорт” ввести валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте поле “Телефон””


#9 Отправка формы на покупку тура в кредит при вводе невалидных данных поле “Паспорт”
Шаги:

* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” валидные данные
* ввести в поле “Паспорт” ввести невалидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Проверьте поле “Паспорт””


#10 Отправка формы на покупку тура в кредит при вводе валидных данных и отказе в предоставлении кредита


Шаги:


* открыть форму покупки тура
* кликнуть кнопку “купить в кредит”
* в открытой форме заполнить поле “Фамилия” валидными данными
* в открытой форме заполнить поле “Имя” валидными данными
* ввести в поле “Телефон” валидные данные
* ввести в поле “Паспорт” ввести валидные данные
* кликнуть кнопку “Отправить заявку”

Ожидаемый результат: переход на страницу с сообщением “Отказано в предоставлении кредита. Обратитесь за помощью к оператору””



_Перечень используемых инструментов:_ Gradle, Idea, JUnit, Selenide, JDK 11, lombok


*П*е*речень и описание возможных рисков при автоматизации:* Изменения на сайте, баги, изменение кредитной истории


_Интервальная оценка с учётом рисков:_ 150 часов


_план сдачи работ:_ 17 ноября 2024 года


