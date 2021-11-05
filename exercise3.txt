a=str(input("Enter your email:"))

def email(a):
    while True:
        if "@" and "." in a:
            print("Email is true")
            return True
        else:
            print("Email is wrong")
            return False

email(a)