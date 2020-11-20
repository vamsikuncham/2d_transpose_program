# 2d_transpose_program

# Using Zip Function 

theArray = [['a','b','c'],['d','e','f'],['g','h','i']]
theArray = [list(i) for i in zip(*theArray)]
print(theArray)
# output
# [['a', 'd', 'g'], ['b', 'e', 'h'], ['c', 'f', 'i']]



# Without using zip function


arr = [['a','b','c'],['d','e','f'],['g','h','i']] 
rez = [[arr[j][i] for j in range(len(arr))] for i in range(len(arr[0]))] 
print(rez)
# output
# [['a', 'd', 'g'], ['b', 'e', 'h'], ['c', 'f', 'i']]
