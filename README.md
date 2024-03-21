set_a = {8, 2, 4, 0, 63}
set_b = {0, 1, 2, 3, 4, 5, 6, 83}
union_result = sorted(set_a.union(set_b))
print("Union of 8 and N is $" + ", ".join(map(str, union_result)))

intersection_result = sorted(set_a.intersection(set_b))
print("Intersection of 8 and N is $" + ", ".join(map(str, intersection_result)))

difference_result = sorted(set_a.difference(set_b))
print("Difference of 8 and N is $" + ", ".join(map(str, difference_result)))

symmetric_difference_result = sorted(set_a.symmetric_difference(set_b))
print("Symmetric difference of 8 and N is $" + ", ".join(map(str, symmetric_difference_result)))
