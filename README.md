s=input("enter the string:")
n=len(s)
for i in range(0,n):
    for j in range(0,i):
        print(s[j],end='')
    print("")

output
enter the string:hijk

h
hi
hij
