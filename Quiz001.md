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
<img width="995" alt="Screenshot 2021-11-11 at 18 38 04" src="https://user-images.githubusercontent.com/89366347/141274922-49cb13a5-f8c9-4d5a-b255-50620f791596.png">
