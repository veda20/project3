# project3
# code snippets to access elements from a tuple , assign elements to different lists , deleting different dictionary elements. 
# 1. assigning elements to different lists
list1 = [1, 2, 3, 4 ,5 ,6 ,7]
print ("the list is : "  + str(list1))
var1 , var2 , var3 = [list1[i] for i in (0 , 2, 5)
print(" the variables are : " + str(var1)+" " + str(var2)+" " +str(var3))

# 2. accessing different elements of a tuple.
list2 = [(1 , yash , 19) , (2 , ajay ,18) , (3 , kate , 21)]
print("the given list is : " + str(list2))
res = [lis[1] for lis in list2]
print("list with the tuple names: " +str(res))

#3.deleting different dictionary elements.
my_dict = {1:'mantha' , 2:'raghavi' , 3:'veda' , 4:'samhitha'}
for key in my_dict.keys():
 if key == 2:
  del my_dict[key]
print(my_dict)
