# Cálculo-diferencial-
print("Iniciante com derivadas e integrais")
from sympy import *
x, y, z = symbols('x y x')
init_printing(use_unicode=True)
diff( 5*x**3+ cos(x), x )
integrate ( 15*x**2 -sin(x),x)
integrate (  15*x**2 -sin(x),( x, 0, 2) )
