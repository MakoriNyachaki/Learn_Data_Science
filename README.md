# Learn_Data_Science
Learning Data Science and Tracking my Progress Each Day

## Data Types
#### String
* Used to store a collection of characters.
* Use " " or ' ' or  """ """ to create strings.
* A string is immutable.

#### Numbers
* Types: _int,_ _float,_ and _complex_
* Conversion: _complex(),_ _int(),_ and _float()_.
* Math operations in order: (), **, *, /, +, -

#### Handling inputs and outputs
* Use the _input(prompt)_ to take the input from the user.
* The entered input will be converted into a  string by default
* Use Python's inbuilt _print()_ function to print output.

## Data Structures
#### Lists
* A list is mutable and ordered collection of items.
* Syntax: _list((1,2,3,4))_ or _[1,2,3,4]_

#### Tuples
* Is an immutable and ordered sequence.
* Syntax: _tuple((1,2,3))_ or _(1,2,3)_
* Are 0-based index just as lists.

#### Dictionaries
* A dictionary is a mutable key value pairs to store a collection.
* Syntax: _{key:value}_ or _dict({key:value})_

#### Sets
* A set is unordered and immutable collection.
* They do not support duplicates.
* Syntax: _{1,2,3}_ or _set([1,2,3])_

## Comparisons and Logic in Python

#### Comparing Variables
* We use _<, >, >=, <=, !=, ==_ to compare values.
* Output: Boolean value (True or False).

#### Output from Logic
_and_ operator: *True*  if and only if both sides are _True_.
_or_ operator: *True* if either side is True or both sides are true.
_not_ operator: Reverses the value of the input. Example True to False

#### Conditional Statements
* Using conditional statements for decision making and execute blocks based on condition.
* We use _if, elif, and else_ keywords.

## Loops
Types: _while_ and _for_ loops

#### While Loop
* Repeats a block of code based on condition.
* Start the loop using the _while keyword._

#### For Loop
* Executes a portion of code one for each element in sequence of elements or iterate over collections.
* Use the _for_ keyword for the loop.

## Python Functions
*Function* is a block of related statements to perform actions.
Types: *Built in* and *User Defined* functions.
#### Built-in Functions
* These are defined by default in Python language packages. 
* They are called to work by importing the specific package where they are defined.
* You can call it many times to work as you want.

#### User Defined
* A series of related statements that are defined and coded by the user.
* They are defined using the _def_ keyword.
* You can call it to work as many times as you wish.

#### Anonymous Lambda
* A function without a name.
* Uses _Lambda_ Keyword.
* Can take any number of arguments.
* Uses only a single expression.
* Syntax: _lambda Argument: Expression_
* Return function objects.

### Break Statement
* Using the break statement to break out of a loop.
* You can break both the while and for loops to stop them.
* Use the _break_ keyword.

### Continue Statement
* Use the _continue_ keyword to skip the remaining value and continue with the next.

### for...else Statement
* Use _for_ with _else_ when the loop is not terminated by the _break._

### Check Password

* We use the _range_, _input()_, _if_, _print(),_ and _else_ to check validity of passwords.

## OOP in Python
* Python is an OOP language.
* A class is a user defined data structure for creating instances.
* Syntax: _class <className>_
* You create objects based on a class.
* Class methods are functions which belong to a class. They have attributes and instance attributes.
* ''__init__(self)'' is initial function to help us know the initial state and tell Python what the values are.

#### Inheritance
* Creating a class based on another class thus, inheriting all methods and properties.

#### Polymorphism

## Advanced Foundations
#### List Comprehension
* List coomprehension is a short and easy way to create a list from another sequence.
* Syntax: ''[Exprs for element in sequence if condition]''
* Example:
                    '''
                    x = range(6)
                    evens = [n for n in x if n % 2 ==0]
                    print(evens)
                    '''

#### Built-in Modules
- Python has several built-in modules.
- You must import these modules in order to use them.
- You can import them using _import math_ to import the whole math module or _from math import sin, cos_ to import specific functions from the math module.
- To call a function after importing the whole module we use the _moduleName.functionName()_ or if you import a specific function we use the _functionName()_ notation.

## Data Visualization
#### Math Module
* Import the _math_ module to use Mathematical functions.
* Some Mathematical functions include: sin(), cos(), sqrt(), round(), tan(), log(),...

#### Statistical Module
* The module provides function for math and statistical operations.
* To Import: _import statistics_

## Errors
- Errors are the undesired input in Python.

#### Type Error
* Python will raise a type error when placing a wrong statement or something wrong in the code.

#### Exception Handling
* Using _try_ and _except_ for exception handling when typing something wrong in the code.
* If the _try block_ raises an error, Python will execute the proper except block.
* Syntax:
            '''
            try:
                #code
            except:
                #code
            '''

## Data Handling
#### The IO Module
* We use the IO module to implement file-like object in memory to store data in memory and handle it.

#### The OS Module
* We use the OS module to interact with the operating system.
* It helps us read, write, and delete files. It also help us work with directories and folders.

#### Shutil Module
* This module help us move data files to different directories and folders.

#### The Send2Trash Module
* The module help us send the deleted files to the trash bin instead of removing the files permanently.
* Use this command to install it using Jupyter Notebooks: _!pip install send2trash_

#### The ZipFile Module
* The module is used to compress and extract files and folders.
* Import: _import zipfile_

## Numerical Python (NumPy)
* NumPy is an open source and free Python Library.
* It has a large number of functions which work with n-dimensional arrays.
* You must import it  to be able to use it. 
* _import numpy as np_

#### 1-D Operations
You can do 1-D array math operations using numpy.

*Math functions with 1-D array include: max(), min(), avg(), mean(), stdev(),...*

#### Creating N-D Arrays
#### Math with N-D Arrays
#### Matrices
##### Indexing for Matrices
* Accessing a value: _arrayName[row, column]_

#### Reshaping Arrays

## Pandas Data Analysis
* Pandas is an open source and powerful Python library.
* It is used for Data Analysis, Data Structures, Analyze Files, and Visualization.
* Import: _import pandas as pd_

### Using Pandas
#### Displaying html Contents
                    '''
                    new_url = '#'
                    new_htm = pdf.read(new_url, header=0, index_col=0)[3]
                    '''
* Ensure all packages needed for the operation are installed. Example the _lxml_ package. To install use _!pip install lxml_ package using the notebook.

#### Excel files
* Pandas can be used to extract and analyze excel data.
* We use: _pd.read_excel()_

#### Json Files
* We use: pd.read_json()_

## Matplotlib Data Visualization
* Matplotlib is an open source library used to visualize data with plots and graphs.
* You must import it first to be able to use it.
* Import: _import matplotlib as plt_

#### Histograms
* They are used to show frequency distributions.
* Syntax: _plt.hsit()_

#### Pie Charts
* Syntax: _plt.pie()_

## Seaborn Library
* Seaborn library is a complement to Matplotlib.
* Seaborn is used for advanced graphs and visualization.
* To use it you have to import it.
* _import seaborn as sb_
