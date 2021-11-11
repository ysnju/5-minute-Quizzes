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

<img width="995" alt="Screenshot 2021-11-11 at 18 41 37" src="https://user-images.githubusercontent.com/89366347/141275444-0b6b036c-dcf8-4dde-8e51-9486be6e962f.png">
