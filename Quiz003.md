Given an integer N, show 100 integers with the repeating pattern 0 to N-1, 0 to N-1,... 

[HL] Output the addition of the numbers.

Example
rangePatternN(3)   → 0, 1, 2, 0, 1, 2, 0, 1, 2, 0, 1, 2,....
				                → 99

rangePatternN(5)  → 0, 1, 2, 3, 4, 0, 1, 2, 3, 4, 0, 1,....
                        → 200
```py
def rangePatternN(n):
    counter = 0
    result = ""
    total = 0
    for i in range (100):
        result = result + str(counter) + ','
        total += counter
        if counter >= n-1:
            counter = 0
        else:
            counter += 1
    return result , total

print(rangePatternN(5))
```
<img width="995" alt="Screenshot 2021-11-11 at 18 39 56" src="https://user-images.githubusercontent.com/89366347/141275190-6040813e-b194-4aab-9144-438ee07fa530.png">
