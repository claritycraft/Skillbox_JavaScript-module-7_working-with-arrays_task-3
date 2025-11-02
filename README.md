# En: Skillbox_JavaScript-module-7_working-with-arrays_task-3
# Ru: Skillbox_JavaScript-модуль-7_работа-с-массивами_задание-3

#### Please give this project a star ⭐ if you found it interesting
#### Пожалуйста, поставьте звезду ⭐ если этот проект Вас заинтересовал

#### Ru: в репозитории две папки с двумя разными вариантами решения кода.
#### En: The repository contains two folders with two different versions of the code solution.

### En:
#### Task 1
Task Goal
Create a web application called “Shopping Cart” that displays a sorted list of items and allows users to add new ones.

#### Project Setup
Create a project folder named “Task 3” with the following files:
- index.html
- index.js
- style.css

#### Instructions
- In index.html, create a basic HTML structure and connect the JavaScript and CSS files.
- Build a web application called “Shopping Cart” with the following functionality:
- Display a list of items from an array, sorted in ascending order.
- Add a button labeled “Add Item”.
When clicked, it should open a prompt() window to enter a new item name.
Before adding the item to the array, validate the input.
If the user enters nothing, show an alert() with the message:
“Item name not entered!”
- After adding a new item, the list should be updated in the DOM, maintaining ascending order.

JavaScript allows string comparison similar to numbers. For example:

if ("Apple" > "Avocado") {
  console.log("Apple is greater than Avocado");
}


String comparison is done character by character. In this example, the character “p” is greater than “v”, so "Apple" is considered greater than "Avocado".
For more details, refer to the material on Comparison Operators.

____________________________________________________________________________________________________________________

### Ru:
#### Задача 1

#### Цель задания
Научиться выполнять сортировку элементов в массиве и показывать результат в списке DOM-элементов.

#### Что нужно сделать
Создайте папку проекта «Задача 3»с файлами:

index.html;
index.js;
style.css.

В файле index.html создайте базовую HTML-разметку, подключите файл скрипта и файл CSS-стилей.
Создайте веб-приложение «Корзина покупателя»со следующим функционалом:
На странице из массива должен выводиться отсортированный по возрастанию список товаров.
Предусмотрите возможность добавления нового товара в массив. Для этого создайте кнопку «Добавить товар». Ввод названия осуществляется в окне prompt(), которое отображается при клике на кнопку добавления. Перед добавлением товара в массив обязательно сделайте проверку ввода. Если пользователь ничего не ввёл, покажите alert() с сообщением: «Название товара не введено!»
После добавления нового товара список должен обновиться в DOM-дереве в отсортированном виде по возрастанию.
Подсказка:в JavaScript доступна возможность сравнения строк. Это работает так же, как и с числами. Пример:

if ("Яблоко" > "Арбуз"){
 console.log("Яблоко больше Арбуз")
}

При сравнении строк происходит сравнение каждого отдельного символа. В этом примере символ «Я» больше символа «А», поэтому строка «Яблоко» больше, чем «Арбуз». Подробнее о сравнении строк рассказано в материале «Операторы сравнения».

Выполните минимальную CSS-стилизацию DOM-элементов.

## En: Technologies Used
## Ru: Используемые технологии

- HTML5
- CSS
- JavaScript

## En: License
This project is for educational purposes only. Do not copy or redistribute without permission.

## Ru: Лицензия
Этот проект предназначен исключительно для образовательных целей. Не копируйте и не распространяйте без разрешения.

## En: Demonstration
## Ru: Демонстрация
![7_3-1](https://github.com/user-attachments/assets/22064447-0cb4-4b4f-9577-1d09aa727b2e)
![7_3-2](https://github.com/user-attachments/assets/26560e32-8978-49ea-b3f9-3b65a627ed97)

























