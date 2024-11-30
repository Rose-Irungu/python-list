# python-list
List Manipulation Assignment

Overview

This assignment focuses on performing basic list operations in Python. You will learn how to create a list, manipulate its contents using various methods, and explore Python’s list functionalities such as appending, inserting, extending, removing, sorting, and finding an index.

Steps Performed
Create an Empty List:
An empty list named my_list was initialized.
Append Elements:
The values 10, 20, 30, and 40 were added to the list using the append() method.
Insert an Element:
The value 15 was inserted at the second position (index 1) using the insert() method.
Extend the List:
The list was extended with the elements [50, 60, 70] using the extend() method.
Remove the Last Element:
The last element in the list was removed using the pop() method.
Sort the List:
The list was sorted in ascending order using the sort() method.
Find the Index of a Value:
The index of the value 30 was found using the index() method and printed to the console.
Final Output
After performing all the operations, the list contents were:

[10, 15, 20, 30, 40, 50, 60]
The index of the value 30 was:
3
Usage Instructions
Copy the Python code provided below into a Python file (e.g., list_assignment.py).
Run the file in a Python environment or interpreter.
Observe the printed output for the index of the value 30.
Python Code
python
Copy code
# Step 1: Create an empty list called my_list
my_list = []

# Step 2: Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert the value 15 at the second position in the list
my_list.insert(1, 15)

# Step 4: Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element from my_list
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
Key Learning Outcomes
Mastering list operations like append, insert, and extend.
Understanding how to manipulate list elements using pop and sort.
Using the index() method to locate a specific element within a list.


Happy coding.😊😊
