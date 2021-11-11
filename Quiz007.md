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
<img width="995" alt="Screenshot 2021-11-11 at 19 07 56" src="https://user-images.githubusercontent.com/89366347/141279456-fd3e89e1-45fe-4655-b4af-5dd7087e8230.png">

Flowchart
![IMG_1298E3FC3D73-1](https://user-images.githubusercontent.com/89366347/141286582-1491d32e-939a-43d2-8a03-ad1dc15c819f.jpeg)
