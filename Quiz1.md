Quiz1
Given 2 numbers, A and B, Output TRUE if one of them is 20 or if their sum is 20.

Examples

Makes20(9, 20) → TRUE
Makes20(9, 9) → FALSE
Makes20(11, 9) → TRUE

```py

def twentymaker(a:int,b:int):
    result = False
    if a+b == 20:
        result = True

    else:
        if a == 20 or b == 20:
            result = True
        else:
            result = False
    return result
print(twentymaker(3,16))




```
