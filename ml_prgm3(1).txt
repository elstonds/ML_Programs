def count_range_in_list(li, min, max):
	ctr = 0
	for x in li:
		if min <= x <= max:
			ctr += 1
	return ctr
print("the count is :")
list1 = [10,20,30,40,40,40,70,80,90]
print(count_range_in_list(list1, 20, 100))
