```py
import random
#make results produced by rarndom the same
random.seed(2022)
list_of_g11 =["Danish","Marika","Minato","Aup","Mitsuki Baba", "Bea","Shine","Fabi","Soraya","Zoopash","Julia","Taichi","Yurika","Kyoka","Elia","Ryu","Leo","Mitsuki Kyotam", "Ming","Marian","Kamilla", "Kojiro","Jun","JiYang","Reiji","Minori","Shimba","Vanni","Nagisa","Boss","Nina","Hana","David","Michel","Asahi","Yuki","Janet","Anju","Andy"]
group = [[],[],[],[],[],[],[],[]]
#minimum amount of assigning students to group(grade number is 38)
min_a = 38



#remove student

while len(list_of_g11) >= 0:
    # choose student
    person_number = random.randint(0,min_a)
    # choose group
    group_number = random.randint(0, 7)
    if len(group[group_number]) < 5:
        group[group_number].append(list_of_g11[person_number])
        print(f"{list_of_g11[person_number]} is in group{group_number+1}")
        # remove student
        list_of_g11.remove(list_of_g11[person_number])
        min_a -= 1

    if min_a<0:
        break
print(group[0])
print(group[1])
print(group[2])
print(group[3])
print(group[4])
print(group[5])
print(group[6])


```

<img width="2034" alt="Screenshot 2022-03-31 at 18 43 06" src="https://user-images.githubusercontent.com/89366347/161026600-19f6583a-013b-4211-bd22-902c0f374985.png">
