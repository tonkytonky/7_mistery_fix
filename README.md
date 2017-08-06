# Решатель квадратных уравнений

Скрипт для решения квадратных уравнений.

# Как использовать

Для запуска решателя перейдите в папку со скриптом и вызовите интерпретатор Python на файл скрипта.
Затем введите 3 коэффициента квадратного уравнения, разделённые пробелом.  

БУДЬТЕ ВНИМАТЕЛНЫ! Скрипт не умеет обрабатывать ошибки ввода, поэтому вам необходимо ввести ровно 3 числа разделённые пробелом. После последнего числа пробел ставить не нужно. 

Ниже приведены примеры трёх возможных вариантов ответа решателя:  
1. Уравнение имеет решение и существуют 2 корня.  
2. Уравнение имеет решение и существует один корень.  
3. Уравнение не имеет решения.  
```
>>> /7_mistery_fix/python quadratic_equation.py
>>> 1 2 -3
(-3.0, 1.0)

>>> /7_mistery_fix/python quadratic_equation.py
>>> 1 -2 1
(1.0, None)

>>> /7_mistery_fix/python quadratic_equation.py
>>> 1 2 3
(None, None)
```


# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
