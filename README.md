numbers = [3,4,1,9,6,2,8]
print(numbers)
x = int(input(&quot;Enter the number to be inserted: &quot;))
y = int(input(&quot;Enter the position: &quot;))
numbers.insert(y,x)
print(numbers)
output
Enter the number to be inserted: 7
Enter the position: 3
[3, 4, 1, 9, 6, 2, 8]
[3, 4, 1, 7, 9, 6, 2, 8]
