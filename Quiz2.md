Quiz2
Given three integer values A,B, and C, output the largest difference between any of the numbers.

Examples
LargestDistance(1,2,3)→2
largestDistance(1,3,10)→9
largestDistance(3,2,4)→2

```py
def difference (a,b,c:int):
    result = 0
    if a == b == c :
        result = 0
    if a == b < c or a < b == c:
        result = c - a
    if a == c < b or a < c == b:
        result = b - a
    if b == a < c or b < a == c:
        result = c - b
    if b == c < a or b < c == a:
        result = a - b
    if c == a < b or c < a == b:
        result = b - c
    if c == b < a or c < b == a:
        result = a -c

    return result

print(difference(10,5,5))


```
