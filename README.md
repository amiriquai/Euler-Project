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

Q6


A=1000000
c=[]
for i in range(2,A):
    for j in range (2, (i-1)):
        if (i%j == 0): 
            if i not in c:
                c.append(i)

x=[]
for i in range(2,A):
    if i not in c:
        x.append(i)
        
print(x[10000])

Q7

a=[]
B =str(7316717653133062491922511967442657474235534919493496983520312774506326239578318016984801869478851843858615607891129494954595017379583319528532088055111254069874715852386305071569329096329522744304355766896648950445244523161731856403098711121722383113622298934233803081353362766142828064444866452387493035890729629049156044077239071381051585930796086670172427121883998797908792274921901699720888093776657273330010533678812202354218097512545405947522435258490771167055601360483958644670632441572215539753697817977846174064955149290862569321978468622482839722413756570560574902614079729686524145351004748216637048440319989000889524345065854122758866688116427171479924442928230863465674813919123162824586178664583591245665294765456828489128831426076900422421902267105562632111110937054421750694165896040807198403850962455444362981230987879927244284909188845801561660979191338754992005240636899125607176060588611646710940507754100225698315520005593572972571636269561882670428252483600823257530420752963450)
for i in range (0,987):
    c = int(B[i])*int(B[i+1])*int(B[i+2])*int(B[i+3])*int(B[i+4])*int(B[i+5])*int(B[i+6])*int(B[i+7])*int(B[i+8])*int(B[i+9])*int(B[i+10])*int(B[i+11])*int(B[i+12])
    D = a.append(c)  

    print(max(a))
