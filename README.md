# program-35
s=input("input a string:")
d=l=0
for c in s:
if c.isdigit():
d=d+1
elif c.isalpha():
l=l+1
else:
pass

print("letter",l)
print("digit",d)
Output:
input a string:jeni
letter 1
digit 0
letter 2
digit 0
letter 3
digit 0
letter 4
digit 0
