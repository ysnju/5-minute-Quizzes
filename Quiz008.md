'''py
def maxabs(n:list):
    max = 0 #this is called precondition
    for i in n:
        if abs(i)>max:
            max = abs(i)
    return f"mas absolute is {max}"
print(maxabs([1,9,-20]))
'''
