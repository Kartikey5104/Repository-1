# Repository-1
#Code no 1
# Python3 program to convert a
# list into a tuple
def convert(list):
	return tuple(list)

# Driver function
list = [1, 2, 3, 4]
print(convert(list))



#Code  no 2
def index_on_inner_list(list1, list2):
    result = [x for x in list1 if x not in list2]
    return result

list1 = [1,2,3,4,5,6,7,8,9,10]
list2 = [2,4,6,8]

print("Original lists:")
print("list1:", list1)
print("list2:", list2)

print("\nRemove all elements from 'list1' present in 'list2:")
print(index_on_inner_list(list1, list2))

