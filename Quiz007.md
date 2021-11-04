Quiz007

```py
def letters(l):
    #empty list
    list = []
    result = 0
    n = len(l)
    #loccation notation[a] would add until i is n so first it is 0
    a = 0
    for i in range(0,n):
        result = f"{i}->{l[a]}"
        list += result
        a += 1
    return list

print(letters("hello"))


```
