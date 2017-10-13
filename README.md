# Решатель квадратных уравнений

This function is intended to find the roots of the quadratic equation. On the input takes the coefficients of the quadratic equation (a, b, c) Returns a list of real roots or None for complex roots

# Как использовать

On the input takes the coefficients of the quadratic equation (a, b, c) Returns a list of real roots or None for complex roots

Usage:
from quadratic_equation import get_roots

print("a*x^2 + b*x + c = 0")
a =input ("Input a:   ")
b =input ("Input b:   ")
c =input ("Input c:   ")

print(get_roots(float(a),float(b),float(c)))

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5 или 2.7

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
