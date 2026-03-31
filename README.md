# *NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y*

_AIM:_
To write a Python program using NumPy that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y.

_ALGORITHM:_

Import NumPy: Import the NumPy library.
Define Arrays: Define two NumPy arrays, x and y, with the same shape (i.e., same number of elements).
Use Boolean Indexing:
x > y gives a boolean array where elements of x are greater than y.
x == y gives a boolean array where elements of x are equal to y.
Find Indices: Use np.where() to get the indices where the conditions x >= y are satisfied.
Print Indices: Print the indices where the condition holds true.

_PROGRAM:_

<img width="475" height="312" alt="image" src="https://github.com/user-attachments/assets/1684c805-37e0-4b69-a160-c8c942f4dbaf" />

_OUTPUT:_

<img width="607" height="292" alt="image" src="https://github.com/user-attachments/assets/bdffd8a5-5d9d-4414-8627-0659b46de259" />

_RESULT:_

Thus , the program has been executed succesfully.

# *NumPy Program: Column-wise Sorting of a 2D Array*

_AIM:_
To write a NumPy program that sorts the elements in each column of a given 2D array in ascending order.

_ALGORITHM:_

Import NumPy: Start by importing the NumPy library.
Get Input: Accept a 2D NumPy array from the user.
Sort Column-wise: Use the np.sort() function with axis=0 to sort each column in ascending order.
Store Result: Store the sorted result in a new array.
Display Output: Print the original array and the column-wise sorted array.

_PROGRAM:_

<img width="348" height="181" alt="image" src="https://github.com/user-attachments/assets/5632bc5e-9fa5-40fa-90b9-096cfde9c3f0" />

_OUTPUT:_

<img width="919" height="652" alt="image" src="https://github.com/user-attachments/assets/b0f68fd3-06d9-4bc9-944d-940ba52adce2" />

_RESULT:_
Thus , the program has been executed succesfully.

# *NumPy Program: Replace the Second Column in a 2D Array*

_AIM:_
To write a NumPy program that deletes the second column from a given 2D array and inserts a new column at the same position.

_ALGORITHM:_

Import NumPy: Start by importing the NumPy library.
Get Input: Get a 2D NumPy array and a new column (as another array) from the user.
Delete Column: Use np.delete() to remove the second column (index 1) from the original array.
Insert Column: Use np.insert() to insert the new column at the second column's original position.
Display Result: Print the updated array with the replaced column.

_PROGRAM:_

<img width="577" height="170" alt="image" src="https://github.com/user-attachments/assets/99f19b0b-79e5-41b9-aec1-ebdb4029f7ca" />

_OUTPUT:_

<img width="307" height="212" alt="image" src="https://github.com/user-attachments/assets/8a37fb8f-4fba-4a2c-bcee-bae97bda62e6" />

_RESULT:_
Thus , the program has been executed succesfully.

# *Pandas Program: Create and Display a DataFrame with Custom Index Labels*

_AIM:_
To create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows.

_ALGORITHM:_

Import Libraries: Import the required libraries – pandas and numpy.
Create Dictionary: Define a dictionary exam_data with keys: 'name', 'score', 'attempts', and 'qualify'.
Index Labels: Create a list of custom index labels called labels.
Create DataFrame: Use pd.DataFrame() to create the DataFrame by passing the dictionary and index labels.
Display Output: Display the DataFrame using print() or by simply calling the DataFrame variable.

_PROGRAM:_

<img width="383" height="148" alt="image" src="https://github.com/user-attachments/assets/39981349-ca40-44d3-98c4-c81045291e9c" />

_OUTPUT:_

<img width="1034" height="324" alt="image" src="https://github.com/user-attachments/assets/a72069bc-52f7-4445-baf3-1a71b408b991" />
<img width="1033" height="366" alt="image" src="https://github.com/user-attachments/assets/99319c5a-41e0-49e0-ba89-5971a0bf3cdb" />

_RESULT:_
Thus , the program has been executed succesfully.

# *🧪 Pandas Program: Join Two DataFrames Along Rows*

_AIM:_
To write a Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame.

_ALGORITHM:_

Import Libraries: Import the pandas library.
Create First DataFrame: Use a dictionary to create student_data1.
Create Second DataFrame: Use another dictionary to create student_data2.
Concatenate DataFrames: Use pd.concat() with axis=0 to concatenate both DataFrames row-wise.
Display Result: Print the new combined DataFrame.

_PROGRAM:_

<img width="559" height="325" alt="image" src="https://github.com/user-attachments/assets/1d27181e-97fc-4b8c-855a-2c48313030b7" />

_OUTPUT:_

<img width="1033" height="171" alt="image" src="https://github.com/user-attachments/assets/92c60a33-41cc-4d98-b537-92d6e78a20f4" />
<img width="1004" height="823" alt="image" src="https://github.com/user-attachments/assets/3226ea07-db2a-4ede-a1bd-a231bd2d3ebb" />

_RESULT:_
Thus , the program has been executed succesfully.
