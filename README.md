[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15304620&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

       Python is a high-level, interpreted programming language known for its simplicity and readability. Key features include:

          -Simple and Easy to Learn: Python's syntax is straightforward and resembles natural language, making it accessible for beginners.
          -Versatile: It supports multiple programming paradigms (procedural, object-oriented, and functional programming).
          -Large Standard Library: Python comes with a comprehensive library for tasks like web development, data analysis, and scientific computing.
          -Community Support: Python has a large and active community that contributes to its libraries and frameworks.

       Examples of effective use cases:

          -Web Development: Frameworks like Django and Flask for building web applications.
          -Data Science: Libraries like NumPy, Pandas, and SciPy for data manipulation and analysis.
           -Scripting: Automating tasks and system administration.
          -Machine Learning: Libraries like TensorFlow and PyTorch for developing AI models.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

      Windows: Download Python installer from python.org, run installer, check "Add Python to PATH" during installation.

       To verify:

              Open terminal or command prompt.
              Type python --version or python3 --version to check installed Python version.
              
              
         Setting up virtual environment:

              Install virtualenv using pip install virtualenv.
              Create a virtual environment: virtualenv venv_name.
               Activate virtual environment:
               Windows: venv_name\Scripts\activateindows: Download Python installer from python.org, run installer, check "Add Python to PATH" during installation.



3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

        # Simple Hello World program
             print("Hello, World!")

             print(): Python function to output text to the console.
             "Hello, World!": String literal enclosed in double quotes.
             Comments: Lines starting with # are comments, ignored by Python.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

        Basic data types:

             Integers (int): Whole numbers, e.g., 42.
             Floating-point numbers (float): Real numbers with a decimal point, e.g., 3.14.
             Strings (str): Sequence of characters enclosed in quotes, e.g., "Hello".
             Booleans (bool): Represents True or False.

      # Variables of different data types
            num1 = 42       # Integer
            num2 = 3.14     # Float
             name = "Derick"  # String
            is_student = True  # Boolean

      # Printing variables
         print(num1)
          print(num2)
          print(name)
          print(is_student)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

      

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

       Functions are reusable blocks of code that perform a specific task. They improve code readability, modularity, and maintainability.

       # Function to add two numbers
          def add_numbers(a, b):
                 return a + b
 
     # Calling the function
          result = add_numbers(3, 5)
          print("Sum:", result)  # Output: Sum: 8


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

       Lists: Ordered collection of items, accessed by index.
       Dictionaries: Unordered collection of key-value pairs, accessed by keys.

       # List of numbers
numbers = [1, 2, 3, 4, 5]

# Dictionary of key-value pairs
person = {"name": "Alice", "age": 30, "city": "New York"}

# Accessing elements
print(numbers[0])       # Accessing list element
print(person["name"])   # Accessing dictionary value

# Adding elements
numbers.append(6)       # Adding to list
person["email"] = "alice@example.com"  # Adding to dictionary

# Iterating through elements
for num in numbers:
    print(num)

for key, value in person.items():
    print(key, ":", value)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

        



9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

      Modules are Python files containing functions, classes, and variables. Packages are directories of modules.

   # Importing math module
import math

# Using math functions
print(math.sqrt(16))   # Output: 4.0 (Square root)
print(math.pi)         # Output: 3.141592653589793 (Value of pi)


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


