# Euler-Project Q1
Q1.

a=[]
for i in range(0,1000):
    if (i%3==0 or i%5==0):
        x = a.append(i)

sum(a)


Q2. 


a=[1,2]
a=[1,2]

for i in range(1,100):
    b = a[i]+a[i-1]
    a.append(b)
    

c=[]
for i in range(1,100):
    if (a[i]%2 == 0):
        c.append(a[i])


sum([i for i in c if i < 4000000])

Q3. 
a=[]
A=600851475143
for i in range(2,A-1):
    if A%i == 0:
        #print(i)
        a.append(i)


c=[]
for i in range(0,len(a)):
    for j in range (2, (a[i]-1)):
        if (a[i]%j == 0): #& a[i] not in c:
            if a[i] not in c:
                 c.append(a[i])
#print(c)
x=[]
#print(c)
for i in range(0,len(a)):
    if a[i] not in c:
        x.append(a[i])
        
print(max(x))

Q4.

a=[]
for i in range (100,999):
    for j in range (100,999):
        a==a.append(i*j)

b=[]
for f in range (0,len(a)):
    for k in range (0,len(str(a[f]))): 
            if int((str(a[f])[len(str(a[f]))-1-k]))-int((str(a[f])[k])) != 0: 
                break
    else:
                b==b.append(a[f])
print(max(b))

Q5

m=[]
for n in range (2,1000000000):
    for i in (2,5,7,8,9,11,13,17,19):
        if n%i!=0:
            break
    else:
        m==m.append(n)
            

print(min(m)))

Q6

def sum_of_square(a):
    b=[]
    i=0
    while i <= a:
        i**2
        b.append(i**2)
        i+=1
    return sum(b)


def square_of_sum(c):
    d=[]
    j=0
    while j <= c:
        d.append(j)
        j+=1
    return (sum(d))**2

square_of_sum(100)-sum_of_square(100)
