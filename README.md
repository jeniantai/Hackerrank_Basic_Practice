# Hackerrank_Basic_Practice

## Objective 
In this challenge, we review some basic concepts that will get you started with this series. You will need to use the same (or similar) syntax to read input and write output in challenges throughout HackerRank. Check out the [Tutorial](https://www.hackerrank.com/challenges/30-hello-world/tutorial) tab for learning materials and an instructional video!

## Task 
Consider a list (list = []). You can perform the following commands:

```insert``` i e: Insert integer  at position .
```print```: Print the list.
```remove```: Delete the first occurrence of integer .
```append```: Insert integer  at the end of the list.
```sort```: Sort the list.
```pop```: Pop the last element from the list.
```reverse```: Reverse the list.

Initialize your list and read in the value of  followed by  lines of commands where each command will be of the  types listed above. Iterate through each command in order and perform the corresponding operation on your list.

### Input Format

The first line contains an integer, , denoting the number of commands.
Each line  of the  subsequent lines contains one of the commands described above

### Constraints

The elements added to the list must be integers.

### Output Format

For each command of type print, print the list on a new line.

### Sample Input
```python
12
insert 0 5
insert 1 10
insert 0 6
print
remove 6
append 9
append 1
sort
print
pop
reverse
print
```
### Sample Output
```python
[6, 5, 10]
[1, 5, 9, 10]
[9, 5, 1]
```
