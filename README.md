# PythonFundamentalsfor-Data-Analyst
Happy learning the basics for beginners!

Python Fundamentals for Data Analyst is a beginner-friendly course covering essential Python programming concepts and key libraries like Pandas and NumPy. Participants will learn data manipulation, statistical analysis, and visualization techniques, gaining practical skills for data analysis tasks.

## Understanding Python Data Types
Provides a comprehensive overview for learners aiming to grasp the fundamentals of Python's diverse data types. Through clear explanations and practical examples, participants will explore essential concepts such as strings, lists, tuples, dictionaries, and sets. This course equips beginners with the foundational knowledge needed to manipulate and manage data efficiently in Python, setting them on the path to becoming proficient programmers.

## Number
     
   1. Integer
       Integer are positive or negative whole numbers (no fractions or decimals). In Python, there is no limit to how long an      integer value can be.
     
   2. Float
      A float is a real number with a floating-point representation. It is specified by a decimal point. 

   3. Complex
      Complex data types in Python consist of two values ​​as real part and imaginary part `j`.

### String
Strings are arrays of bytes representing Unicode characters, a string is a collection of one or more characters put in a single quote `(‘ ’)`, double-quote `(“ ”)`, or triple-quote `(‘“ ”’)`.

### Boolean
Boolean or bool represents either True or False, used for logical operations and conditions.

### List
List is a data structure in Python that is a mutable, or changeable, ordered sequence of elements. Each element or value that is inside of a list is called an item

### Tuple 
Tuples are used to store multiple items in a single variable. A tuple is a collection that is ordered and unchangeable. Tuples are written with round brackets.

### Set
Sets are used to store multiple items in a single variable. A set is a collection that is unordered, unchangeable*, and unindexed. Set items are unchangeable, but you can remove items and add new items. Sets are written with curly brackets.

### Dictionary (dict) 
Dictionaries are used to store data values in key: value pairs. A dictionary is a collection that is ordered*, changeable, and does not allow duplicates. Dictionaries are written with curly brackets and have keys and values.

### Arithmetic Operators
  1. Addition `“ + ”` : Adds two operands
  2. Subtraction `“ - ”` : Subtracts the right-hand operand from the left-hand operand.
  3. Multiplication `“ * ”` : Multiplies two operands.
  4. Division `“ / ”` : Divides the left-hand operand by the right-hand operand (always results in a floating-point number).
  5. Modulus `“ % ”` : Returns the remainder of the division of the left-hand operand by the right-hand operand.
  6. Exponentiation `“ ** ”` : Raises the left-hand operand to the power of the right-hand operand
  7. Floor Division `“ // ”` : Divides the left-hand operand by the right-hand operand and returns the integer part of the result

### Input and Output
The print() function allows you to present output in different formats, while the input() function facilitates user interaction by collecting input while the program is running.
  1. `Output: print` --> This function allows us to display text, variables, and expressions on the console.
  2. `Input: input()` --> To enable user input in your program, utilize the input() function. Within parentheses (), provide the text to be displayed (prompt), and assign a variable preceding the equal sign (=) to store the user's input. By default, the input() function in Python is utilized for accepting user input, capturing it as a string.

### String Formatting-Argument Specifiers
String formatting involves taking a set of variables and, using an expression, formatting them into a provided string that contains placeholders for those variables. This can be achieved using the "%" operator combined with "argument specifiers." 
#### Common argument specifiers include:
     `%s` - String
     `%d` - Integers
     `%f` - Decimal numbers
     
### Conditional Expressions (IF-ELSE-ELIF)
Conditional expressions, commonly known as the ternary operator in Python, provide a succinct method for creating conditional statements. These expressions enable you to make decisions within a single line of code, enhancing the efficiency and readability of your programs.
  1. IF :
     - In Python, expressions are positioned after the if keyword.
     - Decisions are determined based on the truth value of the expression.
     - If the expression evaluates to True, the block of statements within the if statement is executed.
     - Following convention, this block is indented after the colon (:).
     - If the expression evaluates to False, the next block (after the if statement) is executed.
  2. ELSE : 
     - The else statement can be combined with the if statement to provide an alternative pathway when the condition/evaluation result is False.
     - The else statement is optional and singular.
  3. ELIF
     - Elif is short for else if.
     - Elif serves as an alternative to nested if statements.
     - An if statement can be followed by one or more elif statements (optional & unlimited).
        
### For 
  1. For loop is a function used for iterating over elements in a collection or sequence, such as lists, strings, or ranges.
  2. If the collection or sequence contains expressions, they are evaluated before iteration begins.
  3. The first item in the sequence or list is assigned to the iterating variable.
  4. The block of statements associated with the loop is then executed.
  5. This process repeats for each subsequent item in the sequence until the entire sequence is exhausted.

### Nested For Loops
A nested loop has one loop inside of another. These are typically used for working with two dimensions such as printing stars in rows and columns as shown below.

### Break
The break statement stops the loop and exits, followed by executing the statement after the loop block.
   - If you have a nested loop, break will stop the loop according to which level or loop it is in.
   - However, if it is placed in the second-deepest loop for example, only that loop will stop, not the main loops

### Cotinue
In Python Continue statement is a loop control statement that forces to execute the next iteration of the loop while skipping the rest of the code inside the loop for the current iteration only, i.e. when the continue statement is executed in the loop, the code inside the loop following the continue statement will be skipped for the current iteration and the next iteration of the loop will begin.

### While 
While loop in Python iterates through a block of code as long as the specified condition is true. It consists of the keyword `"while"` followed by a condition. The code inside the loop continues to execute as long as the condition remains true.

Syntax of basic list comprehension in Python : 
`“while condition:” # Code block to be executed repeatedly`

### List Comprehension
List comprehension in Python allows for the concise creation of new lists by condensing the syntax of a for loop and condition into a single line, improving code efficiency and clarity. It's particularly useful for data transformation, filtering, or creating lists based on existing ones.

Syntax of basic list comprehension in Python: 
`“new_list = [expression for an item in iterable]”` 
