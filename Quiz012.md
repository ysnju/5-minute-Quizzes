```py
def wordlength(n:list):
    result = 0
    for i in range(len(n)):
        result += len(n[i])

    final_result = result/len(n)

    return final_result

print(wordlength(["home","car","travel","beach"]))

```
