```py
def wordlength(n:list):
    result = 0
    for i in range(len(n)):
        result += len(n[i])

    final_result = result/len(n)

    return final_result

print(wordlength(["home","car","travel","beach"]))

```

<img width="951" alt="Screenshot 2021-11-18 at 13 49 59" src="https://user-images.githubusercontent.com/89366347/142354618-5d53fc26-c32a-4922-b1d9-0bf395a56f26.png">

