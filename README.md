l=[]
even=0
odd=0
p=0
n=int(input("tc"))
for i in range(n):
    a=int(input("how many"))
    for j in range(a):
        b=int(input())
        l.append(b)
        for x in l:
            if x%2==0:
                even+=1
            else:
                odd+=1
            if even>odd:
                for k in range(a):
                    if l[k]%2!=0:
                        p+=1
            else:
                for l in range(a):
                    if l[l]%2==0
                    p+=1
                    print(l.index(p))
                    
                    
