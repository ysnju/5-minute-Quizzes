```py
#Hard code
def binaryreader(n):
    dec_binary = 0
    result = ""
    binary1 = n[0], n[1], n[2]
    binary2 = n[4], n[5], n[6]
    binary3 = n[8], n[9], n[10]
    result = str(4 * int(binary1[0]) + 2 * int(binary1[1]) + 1 * int(binary1[2]))+str(4 * int(binary2[0]) + 2 * int(binary2[1]) + 1 * int(binary2[2]))+str(4 * int(binary3[0]) + 2 * int(binary3[1]) + 1 * int(binary3[2]))
    return result
print(binaryreader("100!110!001"))
```
<img width="1007" alt="Screenshot 2021-12-06 at 9 35 27" src="https://user-images.githubusercontent.com/89366347/144770602-d0137b05-1f9d-435d-a3d3-c9e33cdb55ef.png">

![IMG_0970](https://user-images.githubusercontent.com/89366347/145704251-0de92622-2e96-432c-af94-5d479c77e7b7.jpg)
