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
