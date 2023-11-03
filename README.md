![Python Version Badge](https://img.shields.io/badge/Created%20in-Python%203.10.12-green?color=ba6c3c&style=plastic)
![Tasks Amount Badge](https://img.shields.io/badge/36%20Tasks%20Completed-green?color=4ebc66&style=plastic)

## Краткое вступление

В данном репозитории находятся решения 36 различных алгоритмических задач, взятых из открытых источников в Интернете, а также из сборника задач по программированию (автор: Златопольский Д. М.).

Формулировки многих задач для большего интереса были дополнены и усложнены.

Исходный код представлен на языке программирования Python (версия интерпретатора = 3.10.12).

Наиболее интересные и сложные задачи, представленные в данном репозитории (на мой взгляд):

- [Решето Эратосфена (поиск последовательности простых чисел)](https://github.com/sudomango/Python-Algo-A/blob/main/Block_03/23%20-%20sieve_of_eratosthenes.py)
- [Различные операции с матрицами (двумерными массивами)](https://github.com/sudomango/Python-Algo-A/blob/main/Block_03/26%20-%20matrix_arithmetic.py)
- [Конвертация чисел в разные системы счислений без использования встроенных в языке методов](https://github.com/sudomango/Python-Algo-A/blob/main/Block_02/20%20-%20dec_to_hex%2C%20hex_to_dec.py)
- [Рекурсивное рисование фигуры "Ёлочка" из ASCII-символов](https://github.com/sudomango/Python-Algo-A/blob/main/Block_02/12%20-%20recursion_tree.py)
- [Факторизация натурального числа (разложение на простые сомножители)](https://github.com/sudomango/Python-Algo-A/blob/main/Block_03/22%20-%20factorize_the_number.py)
- [Два варианта реализации поиска уникальных элементов в списке случайных чисел](https://github.com/sudomango/Python-Algo-A/blob/main/Block_03/30%20-%20unique_elements.py)

С полным списком всех 36 задач и ссылками на исходный код с решениями можно ознакомиться [здесь](https://github.com/sudomango/Python-Algo-A/blob/main/all_tasks_readme.md).

• • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • •

<details><summary>💿 Установка и запуск решений на компьютере:</summary>

<br>

Для запуска скриптов необходимо клонировать [(скачать)](https://github.com/sudomango/Python-Algo-A/archive/refs/heads/main.zip) весь репозиторий.

```shell
git clone https://github.com/sudomango/Python-Algo-A.git
```

Также для запуска 3-ей задачи необходимо установить модуль pytz (Python Timezones):

```shell
pip install pytz
```

Любой скрипт следует запускать **только из каталога, в котором он расположен**, ни из какого другого.

Запуск решений в командной строке Windows:

```shell
cd Block_##
python script_name.py
```

Для Linux команда будет немного отличаться (проверено на Ubuntu Server):

```shell
cd Block_##
python3 script_name.py
```

Далее действуем согласно инструкциям скрипта и условиям конкретной задачи.

</details>

<div style="margin-top: 16px"></div>

• • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • •

## Некоторые примечания

Весь код проверен на работоспособность на Windows 10 и Ubuntu Server 22.04, результат выполнения всегда соответствует поставленному условию задачи.

![Source Code Sreenshot](resources/source_code_screen.jpg)

Весь исходный код **служит для учебных целей**, в связи с чем в нём могут встречаться различные пояснительные комментарии, не всегда оптимальные алгоритмы, отладочная информация и так далее.