import random
number=random.randint(1,100)
while True:
    x=int(input("Enter the your guess:"))
    if x>number:
        print("increase")
    elif x<number:
        print("decrease")
    else:
        print("Victory is yours")
        break