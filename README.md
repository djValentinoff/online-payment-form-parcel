# Форма онлайн-оплаты
### Учебный проект курса Javascript «Продвинутый уровень» онлайн школы Skillbox. #

![Пример формы](example1.png "Пример формы")
![Пример формы с ошибками](example2.png "Пример формы с ошибками")
![Пример формы без ошибок](example3.png "Пример формы без ошибок")

---
**При выполнении задания использовались npm и система сборки Parcel.**<br>**В package.json определены команды dev для запуска сервера разработки и build для сборки проекта.**

**Для запуска приложения пропишите команду в консоли:** 
* __npm i__ - для подтягивания необходимых библиотек и зависимостей.

**Для запуска:**
* __npm run dev__ - команда для запуска сервера разработки.
* __npm run build__ - команда для запуска build сборки проекта.

---
## Стек ##
* Вся логика реализована на чистом Javascript.
* Рендеринг DOM: REdom.
* Стили: Bootstrap
* Валидация карт: Card-validator.
* Валидация email: Email-validator.
* Маска полей: Inputmask.
* Сборка: Parcel.
---

## Что требовалось сделать: #
**При выполнении задания используется npm и система сборки parcel.**<br>**Определить в package.json команды dev для запуска сервера разработки и build для сборки проекта.**

## Сделайте форму для онлайн-оплаты.<br>Форма должна иметь следующие поля для ввода: ##

* номер карты;
* дата окончания действия карты (ММ/ГГ);
* CVC/CVV (3 цифры на обороте карты);
* email для отправки онлайн-чека.
* Все поля обязательны для заполнения.

**При вводе номера карты должны игнорироваться любые символы, кроме цифр. Цифры автоматически разделяются по 4 штуки пробелом. Номер карты должен проходить валидацию на корректность.**

**Дата окончания должна быть строго в формате 00/00, где первые 2 цифры — номер месяца, 3-4 цифры — год. Обязательно разделяйте их символом «/», причём делать это нужно автоматически, если в поле введено 2 цифры месяца. Указанные данные должны быть корректными (месяц от 01 до 12) и больше текущей даты (то есть если сегодня 14 марта 2021 года, то минимально возможная дата — 04/21).**

**В поле для CVC/CVV должно быть введено строго 3 цифры.**

**Email также должен быть указан в корректном формате.**

**Проверка корректности введённого значения должна происходить при потере фокуса на поле (событие blur), а при любом вводе в поле ошибка должна сбрасываться.**

**Под формой нужно расположить кнопку «Оплатить». Она должна быть в состоянии disabled до тех пор, пока пользователь корректно не заполнит все поля. Нажатие на кнопку обрабатывать не нужно.**

## Дополнительное задание (выполнение по желанию): ##
**Сделайте так, чтобы сбоку от поля для ввода появлялся логотип Visa/MasterCard/Мир или другой платёжной системы. В поисковых системах можно легко найти информацию о том, как определить платёжную систему по номеру карты.**


