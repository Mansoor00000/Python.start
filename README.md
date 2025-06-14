# Python.start
## Python-Great-Learning

### 1. Print hello world
print('hello world')

### 2. Write the alphabets 'A', 'B', 'C' on new lines using a single print function
print('A' ,'B' , 'C' , sep= '\n')

### 3. Create a string, a numeric and boolean variables by assigning variable names. Further, check their datatype
mystr = 'hello mansoor'
myint = 10
myfloat  = 4.566
mycomplex = 3+5j
myboolean = True

print(f"mystr:{type(mystr)}")
print(f"myint: {type(myint)}")
print(f"myfloat: {type(myfloat)}")
print(f"mycomplex: {type(mycomplex)}")
print(f"myboolean: {type(myboolean)}")

### 4. Create a complex number and assign it the name 'comp_var' and check its datatype

comp_var = 9.8j
type(comp_var)

### 5. Convert a float variable f = 88.63 to integer

f = 88.63
g = int(f)
type(g)

  ### 6. Create a numeric variable and convert it to a string

int1 = 10
str1 = str(int1)
type(str1)

### 7.  Create two strings and concatenate them using '+' operator

song1 = ('what is it good for')
song2 = ('absolutely nothing!')

result = song1 + " " + song2
print(result)


### 8. Create a string with the name 'Bengaluru' and 'Great Learning' as its element. Perform the following on it
  ##Find its length.
  ##Extract it first two letters.

str1 =  ('Bengaluru' 'Great Learning') 
length = len(str1)
print(length)
str1[0:2]

### 9.  Given the string 'Today is a rainy day.
  ##Write a code to get 'is' and 'day'.
  ##Obtain the last two letters.
  ##Write the statement backwards.

word = ('Today is a rainy day')
s = 'Today is a rainy day' .split()
s = (s[1] , s[4])
print(s)

word[18:20]

reversed = ' '.join(word.split()[::-1])
print(reversed)

### 10.Write a program to perform following list operations on the list given below:
  ##a. Check the length of mix_list_1
  ##b. Concatenate the mix_list_1 and mix_list_2
  ##c. Repeat the mix_list_2 two times
  ##d. Check the membership of 'Data' in mix_list_1

mix_list_1 = ['Data', 'Analysis', 100, 'Python', True, 9098]

mix_list_2 = ['List operations', 101, 789]


length = len(mix_list_1)
print(length)

mixed_list = mix_list_1 + mix_list_2
print(mixed_list)

last_two_item = mix_list_2[::-2]
print(last_two_item)

print('Data' in mix_list_1)
print('Analysis' in  mix_list_1)
print(100 in mix_list_1)
print('Python' in mix_list_1)
print(True in mix_list_1)
print(9098 in mix_list_1)


### 10. Write the program to multiply the two lists. from both zip function and numpy
  ###Lists to perform multiplication:

  ##num_list_1 = [10, 20, 30, 40]

  ##num_list_2 = [2, 2, 2, 2]

num_list_1 = [10, 20, 30, 40]

num_list_2 = [2, 2, 2, 2]

import numpy as np

num_list_1 = [10, 20, 30, 40]

num_list_2 = [2, 2, 2, 2]

result  = np.array (num_list_1) * np.array(num_list_2)

print("Result:" , result)

num_list_1 = [10, 20, 30, 40]

num_list_2 = [2, 2, 2, 2]

result = [x * y for x,y in zip (num_list_1 , num_list_2)]

print(result)


### 11. 11. Write a program to perform following built-in list operations:¶
  ##a. Minimum element of the list
  ##b. Maximum element of the list
  ##c. Sort the elements (use sort() and sorted() function)
  ##d. Create a copy of a list
  ##e. Remove element '-79' from the list


num_list = [90, 83, -79, 10, 0, 12]

print(min(num_list))

print(max(num_list))

num_list = [90, 83, -79, 10, 0, 12]
print(num_list)
num_list.sort(reverse  = True)
print(num_list)
sorted_list = sorted(num_list)
print(sorted_list)

copy_list = num_list.copy()
print(copy_list)

num_list.remove(-79)
print(num_list)

### 12.  Manipulating a list:
  ##a. Add a new element 'Boolean' at index location 0 in the given list
  ##b. Replace an element 'sets' with 'string' in the given list
  ##c. Add elements 'int' and 'complex' to the given list

datatypes_list = ['list', 'tuples', 'dictionary', 'sets']

datatypes_list.insert(0 , 9+5j)
print(datatypes_list)

datatypes_list = ['list', 'tuples', 'dictionary', 'sets']
datatypes_list = [ 'strings' if x == 'sets' else x for x in datatypes_list]
print(datatypes_list)

datatypes_list = datatypes_list + [10 = int, 1+5j = complex]
print(datatypes_list)


