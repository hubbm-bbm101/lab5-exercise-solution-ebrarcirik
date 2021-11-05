 N=int(input("enter a number:"))
liste1=[]
liste2=[]
for i in range(1,N+1):
    if i%2!=0:
        liste1.append(i)
        #liste.append=eklemek
print(sum(liste1))
for a in range(1,N+1):
    if a%2==0:
        liste2.append(a)
print((sum(liste2)/len(liste2)))