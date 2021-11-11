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
<img width="995" alt="Screenshot 2021-11-11 at 19 09 41" src="https://user-images.githubusercontent.com/89366347/141279725-e4b3a34f-72ce-4ce1-b678-3d367c3d6703.png">

Flowchart

![IMG_5321EFB9DB33-1](https://user-images.githubusercontent.com/89366347/141288227-bf3e4590-e5b2-472e-9750-3b68a2eb28e7.jpeg)
