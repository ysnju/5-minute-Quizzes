Quiz005

Given an integer N, show the multiplication table. 

Example
tableM(N=2)   → 2x1=2
					     2x2=4
					     2x3=6

					     2x9=18
```py
def multiplication (n:int):
    equation = 0
    result = 0
    table = []
    for i in range(1,10):
        result = n*i
        equation = f"{n}×{i}={result}"
        table.append(equation)
    return table

test = multiplication(2)
print(test)
```
