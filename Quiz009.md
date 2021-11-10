Quiz009
missing number

```py
def missingnumber(list:list):
    firstnumber = list[0]
    result = 0

    for i in range(1,len(list)):
        if list[i-1]+1 != list[i]:
            result = list[i]-1

    return result

print(missingnumber([1,2,3,4,5,6,8]))

```
