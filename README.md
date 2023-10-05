#hand_cricket
#Have you ever player hand cricket in school? I have tried the replicate the same in python.
import random
target=random.randint(1,20)
print("target is: ",target)

pla=0
for n in range(1,10):
 player=int(input("enter the number(from 1 to 6): "))
 choice=[1,2,3,4,5,6,]
 choosen=random.choice(choice)
 print("system has choosen: ",choosen)
 if player!=1 and player!=2 and player!=3 and player!=4 and player!=5 and player!=6:
     print("enter valid input: ")
 if player!=choice:
    pla=pla+player
 else:
    print("out")

 if pla>=target:
    print("you won")
    break
