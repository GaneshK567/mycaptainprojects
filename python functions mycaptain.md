# mycaptainprojects
developed by GANESH K
list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)

list3 = list1 + list2
print(list3)

tup = (1, "a", "string", 1+2)
print(tup)
print(tup[1])

# Python code to demonstrate
# removal of dict. pair
# using pop()

# Initializing dictionary
test_dict = {"Arushi": 22, "Anuradha": 21, "Mani": 21, "Haritha": 21}

# Printing dictionary before removal
print("The dictionary before performing remove is : " + str(test_dict))

# Using pop() to remove a dict. pair
# removes Mani
removed_value = test_dict.pop('Mani')

# Printing dictionary after removal
print("The dictionary after remove is : " + str(test_dict))
print("The removed key's value is : " + str(removed_value))

print('\r')

# Using pop() to remove a dict. pair
# doesn't raise exception
# assigns 'No Key found' to removed_value
removed_value = test_dict.pop('Manjeet', 'No Key found')

# Printing dictionary after removal
print("The dictionary after remove is : " + str(test_dict))
print("The removed key's value is : " + str(removed_value)) 
