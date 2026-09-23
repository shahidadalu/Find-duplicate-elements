# Find-duplicate-elements
numbers = [1, 2, 3, 2, 4, 5, 3, 6]

duplicates = {x for x in numbers if numbers.count(x) > 1}

print("Duplicates:", duplicates)
