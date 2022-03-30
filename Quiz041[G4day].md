```py
import random
random.seed(2022)
list_of_g11 =["Danish","Marika","Minato","Aup","Mitsuki Baba", "Bea","Shine","Fabi","Soraya","Zoopash","Julia","Taichi","Yurika","Kyoka","Elia","Ryu","Leo","Mitsuki Kyotam", "Ming","Marian","Kamilla", "Kojiro","Jun","JiYang","Reiji","Minori","Shimba","Vanni","Nagisa","Boss","Nina","Hana","David","Michel","Asahi","Yuki","Janet","Anju","Andy"]
print(list_of_g11[0:38:5])
group = [[],[],[],[],[],[],[],[]]
n = 38

#choose student
        #choose group
        #remove student

while len(list_of_g11) >= 0:
    person_number = random.randint(0,n)
    group_number = random.randint(0, 7)
    print(person_number,group_number)
    if len(group[group_number]) < 5:
        group[group_number].append(list_of_g11[person_number])
        print(f"{list_of_g11[person_number]} is in group{group_number}")
        list_of_g11.remove(list_of_g11[person_number])
        print(list_of_g11)
        print(group)
        n -= 1

    if n<0:
        print("done")
        break

```
