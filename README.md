  id(value) - --- variable use to refer objects like any value as -  2,3 etc.
  a,b,c=1,2,4-----------multiple assignment
value = 89
print("current value of your variable is : {} " .format(value))
def change_value(value):
    value = 98
    print("Function is called ....")
change_value(value)
print("now value of your variable is : ",value)
## gloabal variable can not be changed in function 
lis=[1,2,3,4]
def change(li):
    print("i am in function ")
    li=[6,7,8,9]------------# try lis.append(34)-----lis[0]=value
change(lis)
print(lis)
--------------------------------------
count = 1 
def doThis(): 
    global count  // now it will work on global count variable and update count . Can acces any wherever in program
    for i in (1, 2, 3): 
        count += 1
######################################################
question : 
def print_formatted(i):
    for k in range(1,i+1):
        print("%2d"%(k),end="")
        st = str(oct(k))
    
        print("%3s"%(st[2:]),end="")
        st1 = str(hex(k))            
        print("%3s"%(st1[2:].upper()),end="")
        st2 = str(bin(k))
        print("%3s"%(st2[2:]),end="\n")



if __name__ == '__main__':
    n = int(input())
    print_formatted(n)
