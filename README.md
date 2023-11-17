# count-digit

num=int(input("Enter a number"))
dum_num=num
count=0
while num !=0:
   num = num//10
   count = count+1
print("The number", dum_num, "contains", count, "digits") 
