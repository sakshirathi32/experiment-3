Aim:
To understand the concept of tuples in Python and perform different operations using them.

Theory:
A tuple is a built-in data type in Python that allows storing multiple elements in a single variable. Tuples are ordered collections that can contain duplicate values and are immutable, which means their elements cannot be changed once the tuple is created. The elements of a tuple can be accessed using indexing and slicing methods. Python also provides tuple unpacking, which enables assigning the elements of a tuple to multiple variables in a single step. Tuples include basic built-in methods such as count() and index() that help perform simple operations and analyze the stored data.

Algorithm 1: Tuple Unpacking and Distinction Check

Start

Create a tuple named result containing Subject, Marks, and Grade.

Unpack the tuple into three variables: Subject, Marks, and Grade.

Display the value of Subject.

Display the value of Marks.

Display the value of Grade.

If Marks (result[1]) is greater than or equal to 75, display “Distinction.”

Stop

Algorithm 2: Attendance Count and Absence Check

Start

Create a tuple named attendance containing attendance status values (‘P’ for Present and ‘A’ for Absent).

Count the number of ‘P’ using attendance.count('P') and display the total number of present days.

Count the number of ‘A’ using attendance.count('A') and display the total number of absent days.

If the number of absent days is greater than or equal to 1, display “Employee was absent at least once.”

Stop

Conclusion:
Thus, the concept of tuples in Python was successfully studied and various operations such as indexing, slicing, unpacking, and counting elements were performed. It was also understood that tuples are immutable, making them suitable for storing data that should remain fixed and unchanged.
