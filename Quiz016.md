```py
def swap(n):
    result = ""
    swapinput = ""

    for i in range(len(n)):
        if i%2 == 1:
            swapinput = n[i]+n[i-1]
            result += swapinput
    return result

print(swap("12a5"))
```
<img width="1007" alt="Screenshot 2021-12-06 at 9 38 37" src="https://user-images.githubusercontent.com/89366347/144770745-26b4dc02-9bad-4b75-9b51-9c8b50424058.png">
