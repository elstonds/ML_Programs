s=input("enter a sentence :").split()
a=list(set(s))

for i in a:

    print(i,"-",s.count(i))