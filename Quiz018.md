```py
def sum67(input:list):
    add_flag = True
    i = 0
    sum = 0
    number = input[i]

    while i<len(input):
        if add_flag == True:
            number = input[i]
            if number == 6:
                add_flag = False

            else:
                sum+= number

        else:
            number = input[i]
            if number == 7:
                add_flag = True
        i += 1

    return sum

print(sum67([1,2,3,6,99,7,4]))
```
