В Pandas есть два основных типа данных - Series и DataFrame. Начнём с Series. Давайте импортируем Pandas и исследуем объект Series.

Series - это проиндексированный одномерный массив значений. Он очень похож на массив NumPy, и в его основе как раз и лежит массив NumPy. Отличие Series в том, что в нём для каждого элемента можно указать некоторое название (метка - label). В результате можно обращаться к отдельному элементу Series не только по его номеру внутри массива, как в NumPy, но и по значению метки. В этом отношении Series очень похож на словарь (Dictionary). Метки могут быть любого типа данных, необязательно числа или строки.

Pandas DataFrame состоит из нескольких объектов Pandas Series с общими значениями индекса.

Можно создать датафрей с разными индексами, тогда места пустых значений заполнятся NaN
По сути, если Series - это одномерный проиндексированный массив, то DataFrame - многомерный проиндексированный массив, в котором каждый столбец является массивом Series.

Файлы CSV (Comma Separated Values) содержат отдельные значения данных, отделённые друг от друга с помощью знаков-разделителей.
Если Вы НЕ используете виртуальную среду, предлагаемую в этом курсе, то Вам может потребоваться установка библиотек xlrd и openpyxl.
