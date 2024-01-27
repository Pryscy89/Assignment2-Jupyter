# Assignment2-Jupyter
Jupyter  Code.

1. To use set comprehensions, I must first accept a list as input and then use set comprehensions to transform the list into a set.

2. Next, I use the zip function to turn the list into a set, and we display the result.

 FIRST CODE: Set Comprehensions  
 
<img width="1146" alt="Screenshot 2024-01-27 at 10 19 13 AM" src="https://github.com/Pryscy89/Assignment2-Jupyter/assets/114356398/62827597-9255-4e18-beb9-58b34f563066">

SECOND CODE:  Using the zip() Function


<img width="1125" alt="Screenshot 2024-01-27 at 10 21 34 AM" src="https://github.com/Pryscy89/Assignment2-Jupyter/assets/114356398/4af62d95-e64c-424e-8c46-21b07eb0decb">

NOTEBOOK

<img width="1138" alt="Screenshot 2024-01-27 at 10 23 00 AM" src="https://github.com/Pryscy89/Assignment2-Jupyter/assets/114356398/5bfca2ff-ad64-4789-be6b-d85fb6bdfa3a">


CODE #1: 
# Input list
input_list = [1,2,3,4,5,2,3,4,5]
# Output set
output_set = {i for i in input_list}
# Printing the output
print(output_set)

CODE #2:
# Name list 
name = ['ALEX', 'MAURO', 'PRISCILLA']
# Marks list
marks = [23, 34, 45]
# Combining the marks and name list
output = zip(name, marks)
# Converting the zip object to set for printing
output = set(output)
# Printing the output
print(output)
