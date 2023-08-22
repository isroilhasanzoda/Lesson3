![Build Status](https://yandex.ru/images/search?pos=25&img_url=https%3A%2F%2Favatars.dzeninfra.ru%2Fget-zen_doc%2F1722013%2Fpub_64df409cc216b40f6c7ab06a_64df40b6d26a363c0f527953%2Fscale_1200&text=js++%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B++string&rpt=simage&lr=10318)

# What is a Method in java script? #

### Метод — это блок кода, который запускается только при вызове. ###
### Вы можете передавать данные, известные как параметры, в метод. ###
### Методы используются для выполнения определенных действий, и они ###
### также известная как функция ###

![Build Status](https://yandex.ru/images/search?pos=3&img_url=https%3A%2F%2Ffuzeservers.ru%2Fwp-content%2Fuploads%2Ff%2F4%2Fc%2Ff4c996c7c1b12de4406ea5d9c64f94e5.jpeg&text=js+%D1%81%D1%82%D1%80%D0%B8%D0%BD%D1%87+%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B&rpt=simage&lr=10318)

### В ,,, есть 3 вида скобок ###
.1 ' ' = Одинарные кавычки
.2 " " = Двойные кавычки
.3 ` ` = Бэктики кавычки

### Перейдем по методам в js. Конечно же их много но тута будут только востребованные  ###
-charAt() - возвращает символ с указанным индексом : == (at).

-concat() - Метод concat() объединяет две или более строк.

-replace() - Метод replace() ищет в строке значение или регулярное выражение, возвращает новую строку с замененными значениями.

-replaceAll - Похож на replace но этот метод может изменить весь текст в строке.

-split() - Позволяет разбить строки на массив подстрок используя заданную строку разделитель для определенеия места разбития.

-substring() - Метод substring() извлекает символы между двумя индексами (позициями) из строки и возвращает подстроку.

-slice() - Удаляет заданную строку.

-toLowerCase() - Метод toLowerCase() преобразует строку в строчные буквы.

-toUpperCase() - Делает все буквы заглавными.

-trim() - Удаляет пробелы только с обеих старон.

-includes() - Определяет содержит ли строка заданные слова или нет выводит только true=false.

-toString() - Изменяте тип на строку = "string".

-indexOf() - это строковой метод который используется для поиска местоположения в строке.

-repeat() - плюсует при добавлении числа(параметра).


# JavaScript Number methods #

-Math.floor() - Функция Math.floor() округляет число до следующего наименьшего целого числа.
4.5 = 4

-Math.round() - Функция Math.round() возвращает число, округленное до ближайшего целого числа.  
4.6 = 5;
4.2 = 4; 

-Math.ceil() - Метод ceil() округляет десятичное число до следующего наибольшего целого числа и возвращает его.
4.7 = 5;

-Math.Max() - Метод max() находит максимальное значение среди указанных значений и возвращает его.
12,5,2,7 = 12;

-Math.Min() - Метод min() находит минимальное значение среди указанных значений и возвращает его.
12,5,2,7 = 2;

-Math.pow() - Метод pow() вычисляет степень числа, увеличивая второй аргумент в силу первого аргумента.
5, 2 = 25;

-Math.sqrt() - Метод sqrt() вычисляет квадратный корень указанного числа и возвращает
4 = 2;

-Math.abs() - Метод abs() находит абсолютное значение указанного числа (без знака) и возвращает.
-2 = 2;

-Math.random() - Выводит любое рандомное(случайное) число которое мы зададим.
10 = 4

NaN - Функция isNaN() проверяет, является ли значение NaN (не числом) или нет.
" a " = NaN;


# What is array in JS #

### Массив — это объект, который содержит значения (любого типа), особенно в именованных свойствах/ключах, ###
## а скорее в позиции с числовым индексом ###
### В JavaScript массив — это упорядоченный список значений. Каждое значение называется элементом, указанным ###
### индекс. ... Во-первых, массив может содержать значения смешанных типов. Вы также можете добавлять элементы или изменять элементы, обращаясь к значению индекса ###

-pop() - удаляет последний элемент

-push() - добавляет новый элемент в конце

-unShift() -  добавляет новый элемент в начале

-shift() - удаляет первый элемент

-tostring() - изменяет все на страку 

-splice() - Метод splice() изменяет содержимое массива, удаляя существующие элементы и/или добавляя новые.


# JavaScript array methods callback #

### Функция callback будет вызвана с тремя аргументами: ###

### значение элемента (value) ###
### индекс элемента (index) ###
### массив, по которому осуществляется проход (array) ###

-map() - Метод map() создаёт новый массив с результатом вызова указанной функции для каждого элемента массива.

-forEach() - Метод forEach() выполняет указанную функцию один раз для каждого элемента в массиве

-find() - Метод find() возвращает значение первого найденного в массиве элемента, которое удовлетворяет условию переданному в callback функции. В противном случае возвращается undefined.

