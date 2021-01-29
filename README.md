# print-positive-numbers-in-a-range-
by jaswanth krishna
list1= [12,-7,5,64,-14]
print("Actual numbers in the list are :",list1 )
new_list = list(filter(lambda x: x>0, list1))
print("Positive numbers in the list:",new_list)

list2= [12,3,-95,14]
print("Actual numbers in the list are :",list2 )
new_list = list(filter(lambda x: x>0, list2))
print("Positive numbers in the list:",new_list)

