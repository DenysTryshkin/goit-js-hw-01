**Greetings, you are at the finish line of Topic 1!**

By now, you know how to declare variables, distinguish between basic data types, and perform simple arithmetic calculations. You remember the syntax of template literals, know how to use comparison operators, and understand how functions work.

It's time to boost your practical skills in these topics by solving the homework tasks!

* * *

## Homework Task Topic 1. Variables and Types. Basics of Functions

*   Create a repository named `goit-js-hw-01` and clone it to your computer.
*   In the `goit-js-hw-01` folder, create the project structure as shown in the diagram below.


*   Read each task and perform it in the corresponding file.
*   Make sure the code is formatted using `Prettier`, and there are no errors or warnings in the console when opening the live page of the task.
*   Submit the homework to your mentor on the LMS platform.

* * *

## Submission Format:

*   The homework should contain two links: one to the output files (the link to the code repository) and the other to the live page on `GitHub Pages`.
*   Attach a zip file of the repository.

**IMPORTANT**  
Please review the [**Instructions for uploading the working file from the repository to Github**](https://drive.google.com/file/d/1UBw9IkvLmk4hO73ji1ScNkj3_H_vKNvT/view?usp=sharing)

* * *

## Evaluation Criteria:

*   Passed / Failed

* * *

## Task 1. Droid Orders

Perform this task in the file `task-1.js`.

The droid repair station is ready for launch, and the sales department software needs to be written.

Declare a function `makeTransaction`, which expects two parameters, whose values will be provided during its call:

*   `quantity` — the first parameter, a number representing the quantity of droids ordered.
*   `pricePerDroid` — the second parameter, a number representing the price of one droid.

Complete the function code so that it returns a string with a message about the purchase of repair droids: `"You ordered <quantity> droids worth <totalPrice> credits!"`, where:

*   `<quantity>` — the quantity of droids ordered.
*   `<totalPrice>` — the total price of the order, i.e., the price of all the ordered droids.

Use the code below and insert it after declaring your function to test the correctness of its work. The results will be logged to the console.

javascript

Копіювати код

`console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!" console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!" console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"`

Leave this code for mentor review.

* * *

### What the mentor will focus on during the review:

*   The function `makeTransaction(quantity, pricePerDroid)` is declared correctly.
*   Calling `makeTransaction(5, 3000)` returns `"You ordered 5 droids worth 15000 credits!"`.
*   Calling `makeTransaction(3, 1000)` returns `"You ordered 3 droids worth 3000 credits!"`.
*   Calling `makeTransaction(10, 500)` returns `"You ordered 10 droids worth 5000 credits!"`.
*   All results are logged to the console.
*   Calling `makeTransaction` with any valid arguments returns the correct value.

* * *

## Task 2. Shipping Message

Perform this task in the file `task-2.js`.

Declare a function `getShippingMessage`, which expects three parameters, whose values will be provided during its call:

*   `country` — the first parameter, a string representing the country of delivery.
*   `price` — the second parameter, a number representing the total price of the product.
*   `deliveryFee` — the third parameter, a number representing the shipping cost of the product.

Complete the function code so that it returns a string with a message about the shipping of the product to the user's country: `"Shipping to <country> will cost <totalPrice> credits"`, where:

*   `<country>` — the delivery country.
*   `<totalPrice>` — the total price of the order, which includes the price of the product and the shipping fee.

Use the code below and insert it after declaring your function to test the correctness of its work. The results will be logged to the console.

javascript

Копіювати код

`console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits" console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits" console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"`

Leave this code for mentor review.

* * *

### What the mentor will focus on during the review:

*   The function `getShippingMessage(country, price, deliveryFee)` is declared correctly.
*   Calling `getShippingMessage("Australia", 120, 50)` returns `"Shipping to Australia will cost 170 credits"`.
*   Calling `getShippingMessage("Germany", 80, 20)` returns `"Shipping to Germany will cost 100 credits"`.
*   Calling `getShippingMessage("Sweden", 100, 20)` returns `"Shipping to Sweden will cost 120 credits"`.
*   Calling `getShippingMessage` with any valid arguments returns the correct value.

* * *

## Task 3. Element Width

Perform this task in the file `task-3.js`.

Declare a function `getElementWidth`, which expects three parameters, whose values will be provided during its call:

*   `content` — the first parameter, the width of the content.
*   `padding` — the second parameter, the horizontal padding value for each side.
*   `border` — the third parameter, the border thickness value for each side.

The values of all parameters will be strings in the `Npx` format, where N is any integer or decimal number.

Complete the function code so that it returns the total width of the element. When calculating the total width, assume that the value of `box-sizing` is `border-box`.

Use the code below and insert it after declaring your function to test the correctness of its work. The results will be logged to the console.

javascript

Копіювати код

`console.log(getElementWidth("50px", "8px", "4px")); // 74 console.log(getElementWidth("60px", "12px", "8.5px")); // 101 console.log(getElementWidth("200px", "0px", "0px")); // 200`

Leave this code for mentor review.

* * *

### What the mentor will focus on during the review:

*   The function `getElementWidth(content, padding, border)` is declared correctly.
*   Calling `getElementWidth("50px", "8px", "4px")` returns the number `74`.
*   Calling `getElementWidth("60px", "12px", "8.5px")` returns the number `101`.
*   Calling `getElementWidth("200px", "0px", "0px")` returns the number `200`.
*   Calling `getElementWidth` with any valid arguments returns the correct value.


_______________________________________________

**Вітання, ти на фінішній прямій теми 1!**

Вже зараз ти знаєш, як оголошувати змінні, розрізняєш основні типи даних та вмієш виконувати прості арифметичні обчислення, пам’ятаєш синтаксис шаблонних рядків, вмієш використовувати оператори порівняння та знаєш як працюють функції.

Час прокачати практичні навички з цих тем, розв’язуючи задачі домашнього завдання!

  

**Домашнє завдання Тема 1.** **Змінні та типи. Основи функцій**

  

*   Створи репозиторій `goit-js-hw-01` та склонюй його собі на комп’ютер.
*   У папці `goit-js-hw-01` створи структуру проєкта, як показано на схемі нижче.

  

**Зверни увагу!** Імена файлів та папок, а також їх структура вкладеності, мають відповідати вказаній схемі. В іншому разі робота не буде прийнята.

  

![](https://s3.eu-north-1.amazonaws.com/lms.goit.files/429bf2a2-345f-4651-913b-0e9990aac0adFrame%2048582%20%282%29.jpg)

  

*   Прочитай кожне завдання і виконай його у відповідному файлі.
*   Переконайся, що код відформатований за допомогою `Prettier`, а в консолі відсутні помилки і попередження під час відкриття живої сторінки завдання.
*   Здай домашнє завдання на ментору на платформі LMS.

  

**Формат здачі:**

*   Домашня робота містить два посилання: на вихідні файли (посилання на репозиторій з кодом) і живу сторінку на `GitHub Pages`.
*   Прикрiплений файл репозиторію у форматi zip

**ВАЖЛИВО**
Переглянь [**Iнструкцію щодо завантаження робочого файлу з репозиторію на Github**](https://drive.google.com/file/d/1UBw9IkvLmk4hO73ji1ScNkj3_H_vKNvT/view?usp=sharing)

  

**Формат оцінювання:**

*   Залiк / Незалiк

  

  

**Задача 1. Замовлення дроїдів**

  

Виконуй це завдання у файлі `task-1.js`

  

Станція з продажу ремонтних дроїдів готова до запуску, залишилося написати програмне забезпечення для відділу продажів.

  

Оголоси функцію `makeTransaction`, яка очікує два параметри, значення яких будуть задаватися під час її виклику: • `quantity`— перший параметр, число, що містить кількість замовлених дроїдів • `pricePerDroid` — другий параметр, число, що містить вартість одного дроїда

  

Доповни код функції так, щоб вона повертала рядок з повідомленням про покупку ремонтних дроїдів: `"You ordered <quantity> droids worth <totalPrice> credits!"`, де: • `<quantity>` — це кількість замовлених дроїдів • `<totalPrice>` — це загальна вартість замовлення, тобто вартість усіх замовлених дроїдів

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

  

console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"

  

Залиш цей код для перевірки ментором.

  

**На що буде звертати увагу ментор при перевірці:**

  

*   Оголошена функція `makeTransaction(quantity, pricePerDroid)`
*   Виклик `makeTransaction(5, 3000)` повертає `"You ordered 5 droids worth 15000 credits!"`
*   Виклик `makeTransaction(3, 1000)` повертає `"You ordered 3 droids worth 3000 credits!"`
*   Виклик `makeTransaction(10, 500)` повертає `"You ordered 10 droids worth 5000 credits!"`
*   В консоль виведині всі результаті викликів
*   Виклик `makeTransaction` з будь якими-валідними аргументами повертає правильне значення

  

  

**Задача 2. Доставка товару**

  

Виконуй це завдання у файлі `task-2.js`

  

Оголоси функцію `getShippingMessage`, яка очікує три параметри, значення яких будуть задаватися під час її виклику: • `country` — перший параметр, рядок, що містить країну доставки • `price` — другий параметр, число, що містить загальну вартість товару • `deliveryFee` — третій параметр, число, що містить вартість доставки товару

  

Доповни код функції так, щоб вона повертала рядок з повідомленням про доставку товару в країну користувача: `"Shipping to <country> will cost <totalPrice> credits"`, де: • `<country>` — це країни доставки • `<totalPrice>` — це загальна вартість замовлення, що включає вартість товару і його доставки

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

  

console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"

  

Залиш цей код для перевірки ментором.

  

**На що буде звертати увагу ментор при перевірці:**

  

*   Оголошена функція `getShippingMessage(country, price, deliveryFee)`
*   Виклик `getShippingMessage("Australia", 120, 50)` повертає `"Shipping to Australia will cost 170 credits"`
*   Виклик `getShippingMessage("Germany", 80, 20)` повертає `"Shipping to Germany will cost 100 credits"`
*   Виклик `getShippingMessage("Sweden", 100, 20)` повертає `"Shipping to Sweden will cost 120 credits"`
*   Виклик `getShippingMessage` з будь якими-валідними аргументами повертає правильне значення

  

  

**Задача 3. Ширина елемента**

  

Виконуй це завдання у файлі `task-3.js`

  

Оголоси функцію `getElementWidth`, яка очікує три параметри, значення яких будуть задаватися під час її виклику: • `content`— перший параметр, ширина контенту • `padding` — другий параметр, значення горизонтального падінгу для кожної зі сторін • `border` — третій параметр, значення товщини бордера для кожної зі сторін Значення всіх параметрів будуть рядками формату `Npx` де N — це довільне число, ціле або дробове.

  

Доповни код функції так, щоб вона повертала число —загальну ширину елемента. При розрахунку загальної ширини орієнтуйся на те, що значення box-sizing дорівнює `border-box`.

  

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

  

console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200

  

Залиш цей код для перевірки ментором.

  

**На що буде звертати увагу ментор при перевірці:**

  

*   Оголошена функція `getElementWidth(content, padding, border)`
*   Виклик `getElementWidth("50px", "8px", "4px")` повертає число `74`
*   Виклик `getElementWidth("60px", "12px", "8.5px")` повертає число `101`
*   Виклик `getElementWidth("200px", "0px", "0px")` повертає число `200`
*   Виклик `getElementWidth` з будь якими-валідними аргументами повертає правильне значення
