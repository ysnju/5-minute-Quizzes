Quiz004

Write a function that receives an integer N, and returns all its factors. 

[HL] show also the addition of the factors show if the result is the same as N

Example
perfectN(6)   → [1, 2, 3]
				    → TRUE
perfectN(10)  → [1, 2, 5]
				    → FALSE

```py
def perfectN(n:int):
    numberresult = []
    sumresult = False
    total = 0
    if n == 0:
        result = 0
        sumresult = True
    for i in range(1,n):
        if n % i == 0:
            numberresult.append(i)
            total += i

    #If the addition of all of the numberresult is equal to n sumresult is true
    if total - n  == 0:
        sumresult = True
    else:
        sumresult = False

    return numberresult,sumresult

print(perfectN(6))

```
