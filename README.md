# pythan-
aman


//type of variable  here in pythan u don't need to define the variable 
1, string ; namr = "shut up" 
2. bool ; adult = True 
3. int ; age = 10
4.floot ; age = 10.0

print(name)  print(adult)  print(age)

name = input("what is your name ?)
print("hello" + name)
print(first name + " " + last name )

//type coversion 
int(name) 
new = int(name) + 5
pritn(new)

first = input("put the value") 
second = input("put the value)

sum = first + second //gives us string value to get actual ans
sum = int(first) + int(second)
print(sum)
print("sum is" + str(sum))

//string 
name = "Nidhi New"
print(name.upper())
prnt(name.lower())
print(name.find('d')) //if it find d then it return index else -1
print(name.replace("New" , "Rai"))
print(name)
print('N' , in name)) // find is N exist in name if yes then return True else False
print("New" in name)) // same as above is New eist or not

//alzebric parts
print(5/2) //give decimal value 
print(5//2) //gives only integer va;ue here i.e 2
print(5 ** 2) // 5^2
print(2 > 3 or 2 > 1) // True
print(2>3 and 2 > 1) //False
print (not 2 > 3) //True
#comments 

//operator precedence

//IF AND ELSE 
age = 18 
if age >= 18 :
print("your done bro")
print("back to school")

elif age < 18 and age > 3:
print("doing great")

else :
print("child")

//loops
print(range(5)) //0 ,1 , 2, 3, 4

 i = 1
while i < 5 :
print(i)
i++

for i in range(5) :
print(i)

//list (here we can modify after entering the values) they are order

marks = [1  , 0 , 2 , "mark"]
print(marks)
print(marks[3]) //we get mark
print(marks[-1]) //we get mark
print(marks[-2]) //we get 2
print(marks[0 : 2]) // we get 1 and 0 not the last insex
print(marks[1 : 3]) //we get 0 and 2

marks.append(99) //add the element in the end
print(marks)

marks.insert(0 , 88) //add at the index mentined
print(marks[0]) // we get 88
print(88 in marks) // 88 exit in marks if yes return True else False
n = len(marks) // length of marks

marks.clear() //marks got clear
print(marks) 

//break and continue
students = ["ram" , "shyam" , "radha" , "sita"]

for students in students :
 if students == radha :
break :
elif student == shyam :
continue :   //if student is equal to shyam then continue to the next interation don't print that 
print(student)

//toupes (it's like list only but here cannot modify and they are  order
marks = (99 , 98 , 97 , 95 , 97 , 97 )
print(marks.count(97))    //count 97 kite baar aayi h marks  = 3
print(marks.index(97)) // index is 2

//set (avoid duplicacy) it is unorder

marks = {99 , 98 , 97 , 96 , 97 , 97}
print(marks) // print 99 , 98 , 97 , 96

print(marks[0]) //this shows error coz index iteration is not possible here

for i in marks :
print(i)   // print 99 , 98 , 97 , 96

//DISCONARY - use to store key , value in pair

marks = {"english" : 96 , "hindi" : 95}
print(marks["english"]) //prints the value which si 96
marks["physics"] = 99 :
print(marks) // {"english" : 96 , "hindi" : 95 , "physics" :99}
