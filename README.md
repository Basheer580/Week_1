*Task 1: Basic Statistics Calculator*
```
def calculate_statistics(numbers):
    sum = sum(numbers)
    average = sum / len(numbers)
    min_value = min(numbers)
    max_value = max(numbers)
    return sum, average, min_value, max_value

numbers = [1, 2, 3, 4, 5]  # example list of numbers
sum, average, min_value, max_value = calculate_statistics(numbers)

print("Sum:", sum)
print("Average:", average)
print("Min:", min_value)
print("Max:", max_value)
```

*Task 2: Integer to Float Converter*
```
def convert_to_float(n):
    return float(n)

integer = 10  # example integer
float_number = convert_to_float(integer)
print(float_number)
```
