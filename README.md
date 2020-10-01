# BasicsOfPython-PythonSets
s = set([1]) # to make a set
# to add an item to the set
s.add(12)
s.add(85)
print(type(s))
s.remove(1) # to remove an specific item from the set
s1 = s.union({58}) # to add an item to the set by making a new set
print(s)
print(s1)
# to display the items from the first set that has same items to second set
s2 = s.intersection({1, 2, 3})
# to match the items from first list. If one or more elements are there result is false, else true.
s3 = ([1, 25, 54])
print(s.isdisjoint(s3))
s_from_list = set([1, 2, 3, 4])
print(s_from_list)
l = [1, 2, 3, 4]
l_from_list = set(l)
print(l_from_list)
# All are examples of Python Sets.
