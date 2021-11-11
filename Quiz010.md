Quiz010
Biggest neighbour difference
Bigneighbour

```py
def BigNeighbour(x:list):
    result = 0
    for i in range(1,len(x)):
        diff = x[i]-x[i-1]
        if diff > result:
            result = diff

    return result
print(BigNeighbour((1,2,3,5,8,9)))
```
<img width="995" alt="Screenshot 2021-11-11 at 19 10 22" src="https://user-images.githubusercontent.com/89366347/141279819-13a5bca2-9a83-4912-9904-95c1d0e7b2b1.png">
Flowchart
![IMG_0748](https://user-images.githubusercontent.com/89366347/141288591-52bc2602-b42d-479f-b3f8-665308868e8a.jpg)
