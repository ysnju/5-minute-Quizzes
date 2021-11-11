```py
def maxabs(n:list):
    max = 0 #this is called precondition
    for i in n:
        if abs(i)>max:
            max = abs(i)
    return f"mas absolute is {max}"
print(maxabs([1,9,-20]))
```
<img width="995" alt="Screenshot 2021-11-11 at 19 08 21" src="https://user-images.githubusercontent.com/89366347/141279524-83e69e82-2366-43f6-bbac-84d9e669deeb.png">
