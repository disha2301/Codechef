# Codechef

# Task 1

### Question 1 : Correct Code 
k=[3,1,2,'a','b']
for i in k:
    if i=='a':
        break
    else:
        print("A")

errors spotted : 
line 1 : addition of ] at the end 
line 3 : correction for 'a':
line 4 : removal of :
                 
                 
### Question 2 : Correct Code
k = int(input("Enter any number:"))
L=0
for j in range(1,k,2):
    L+=1
    if j%2==0:       
        print("Codechef"*2)
    else:
        print("Codechef"*3)
    print(l)
    
errors spotted :
line 3 : addition of : at the end  
line 4 : uppercase conversion of l
line 5 : correction in the relational operator thereby using == operator
line 9 : use of parenthesis instead of square brackets
                 
### Question 3 : Correct Code
def extendList(val,list=[]):
    list.append(val)
    return list

list1 = extendList(10)
list2 = extendList(123,[2,3])
list3 = extendList(3)

print("list1=",list1)
print("list2=",list2)
print("list3=",list3)

errors spotted :
line 1 : use of , instead of ; and adding : at the end and using = operator instead of == operator
line 5 : correction in the square brackets
line 6 : correction in the shorthand operator thereby using = operator and correction in parenthesis value at the end
line 7 : use of parenthesis instead of square brackets
line 9 : use of parenthesis
                 
### Question 4 : Correct Code
def compound_interest(principle,rate,time):
    principle,rate,time=0,0,0
    Amount=principle*((1+rate/100.0)*time)
    CI=Amount-principle
    print("Compound interest is",CI)
    
p=float(input("Enter the principle "))
r=float(input("Enter the principle "))
t=float(input("Enter the principle "))

compound_interest(p,r,t)

errors spotted : 
line 1 : removal of : from the end
line 5 : uppercase conversion of CI
line 8 : correction of " at the end
line 9 : correction in the input values thereby making it p,r,t


# Task 2  
### Answers :
1. option a : 10
2. option d : 5
3. option c : assignment
4. option a : 1 2 3 4 5 0
5. option d : All of these
6. incomplete question options not given
7. option b : 0.000000
8. option c : Same address is printed
9. option c : 19
10. option a : 1 time
