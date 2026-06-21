d1 = {'a': 10, 'b': 20, 'c': 30}
d2 = {'b': 5, 'c': 15, 'd': 25}

result = d1.copy()

for key in d2:
    if key in result:
        result[key] += d2[key]
    else:
        result[key] = d2[key]

print(result)
