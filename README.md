# Graphing_mathematical_functions_in_Python
from numpy import *
import matplotlib.pyplot as plt

def f(x): return (sin(10 ** x) * sin(3 * x)) / (x ** 2)

t = linspace(0, 1, 50)
y = f(t)
plt.xlabel('x')
plt.ylabel('y')
plt.plot(t, y)
plt.savefig("plot.png")
plt.plot(t, y)
plt.show()
