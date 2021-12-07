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
````
<img width="1007" alt="Screenshot 2021-12-07 at 17 55 33" src="https://user-images.githubusercontent.com/89366347/144997645-789b00f3-c353-4978-a98d-3667f0acb77c.png">

![IMG_0890](https://user-images.githubusercontent.com/89366347/144997454-38a6fa2f-70e3-436c-972c-56d017c06b3d.jpg)
