  id(value) - --- variable use to refer objects like any vlaue as -  2,3 etc.
  a,b,c=1,2,4-----------multiple assignment
value = 89
print("current value of your variable is : {} " .format(value))
def change_value(value):
    value = 98
    print("Function is called ....")
change_value(value)
print("now value of your variable is : ",value)
## gloabal variable can not be chanbged in function 
lis=[1,2,3,4]
def change(li):
    print("i am in function ")
    li=[6,7,8,9]------------# try lis.append(34)-----lis[0]=value
change(lis)
print(lis)
--------------------------------------
![b758f7f597a36ab4a226d21f5348a717](https://user-images.githubusercontent.com/101422337/180610718-faaaf12b-ed25-4446-af36-2eff0d7e062d.jpg)
