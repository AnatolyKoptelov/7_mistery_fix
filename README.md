# Solver of quadratic equations

This function is intended to find the roots of the quadratic equation. 

# How to use it

On the input takes the coefficients of the quadratic equation (a, b, c) 
Returns a tuple of real roots or None for complex roots

Usage example:
``````````````````````````````````````````
from quadratic_equation import get_roots

print("a*x^2 + b*x + c = 0")
a =input ("Input a:   ")
b =input ("Input b:   ")
c =input ("Input c:   ")

print(get_roots(float(a),float(b),float(c)))
````````````````````````````````````````````
# How to run

The script requires the installed Python interpreter version 3.5 or 2.7 for its work

Running on Linux:

```bash
python tests.py # or python3, python2 instead python, it depends of your OS preferenses
```

Running on Windows is simular

# Project Objectives

The code was created for educational purposes. In the framework of the training course on web development - ― [DEVMAN.org](https://devman.org)
