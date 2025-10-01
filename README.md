# 🚀 10 Basic Python Programs for Beginners (Level 1)
A collection of simple Python scripts designed to introduce fundamental programming concepts. Each example is clearly explained and ready to run.

## 1. Hello, World!
This program is the traditional first step in programming. It demonstrates how to output a simple text string to the console.
```python
 Prints the classic "Hello, World!" message
 
     #The `print()` function is used to display output on the screen.
     #Anything inside the parentheses and quotes will be printed as text.
     print("Hello, World!")
```

## 2. Greet the User
This script shows how to take user input from the keyboard and use it to display a personalized message.

 Asks for a user's name and prints a custom greeting
 ```python
    #The `input()` function prompts the user to type something and press Enter.
    #The text you put inside the parentheses is the message shown to the user.
    #The value the user types is stored in a variable called `name`.
    name = input("Enter your name: ")

    # An f-string (the `f` before the quotes) lets you embed variables directly into a string.
    # Here, we insert the value of the `name` variable into our greeting message.
    print(f"Hello, {name}! Welcome.")
```

## 3. Sum of Two Numbers
This example covers basic arithmetic and type conversion by taking two numbers as input, calculating their sum, and displaying the result.

 Calculates the sum of two numbers provided by the user
 ```python
    # `input()` always returns text (a string). To do math, we must convert it to a number.
    # The `int()` function converts a string into an integer (a whole number).
    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))

    # Now we can perform the addition with the two numbers.
    sum_of_numbers = num1 + num2

    # Finally, we print the result using an f-string.
    print(f"The sum is: {sum_of_numbers}")
```

## 4. Even or Odd
This program introduces conditional logic (if-else statements) to determine if a number is even or odd using the modulo operator.

Checks if a given number is even or odd
```python
    # Get a number from the user and convert it to an integer.
    number = int(input("Enter a number: "))

    # The modulo operator `%` gives you the remainder of a division.
    # If a number divided by 2 has a remainder of 0, it is an even number.
    if number % 2 == 0:
        # This line runs only if the condition above is true.
        print(f"{number} is an even number.")
    else:
        # The `else` block runs if the `if` condition is false.
        print(f"{number} is an odd number.")
```

## 5. Simple Loop
This script demonstrates a for loop, a fundamental concept for repeating actions, by printing numbers in a sequence.

 Uses a for loop to count from 1 to 5
```python
    print("Counting from 1 to 5:")

    # A `for` loop repeats a block of code for each item in a sequence.
    # `range(1, 6)` generates a sequence of numbers starting from 1 up to (but not including) 6.
    for i in range(1, 6):
        # The code inside the loop will run 5 times.
        # Each time, the variable `i` will hold the current number (1, then 2, then 3, etc.).
        print(i)
```

## 6. Calculate Area of a Rectangle
A practical example of using variables and arithmetic operations to solve a simple real-world problem.

 Calculates the area of a rectangle
```python
    # `float()` converts the input to a floating-point number (a number with decimals).
    # This is useful for measurements that might not be whole numbers.
    length = float(input("Enter the length: "))
    width = float(input("Enter the width: "))

    # The multiplication operator `*` is used to calculate the area.
    area = length * width

    # Display the final calculated area.
    print(f"The area is: {area}")
```

## 7. Find the Maximum of Two Numbers
This script showcases a concise way to use a conditional expression (a ternary operator) to find the larger of two numbers.

 Finds the larger of two input numbers
```python
    x = int(input("Enter first number: "))
    y = int(input("Enter second number: "))

    # This is a one-line `if-else` statement.
    # It reads: "The value of `max_num` is `x` if `x` is greater than `y`, otherwise it is `y`."
    max_num = x if x > y else y

    # Print the number that was determined to be the maximum.
    print(f"The maximum number is: {max_num}")
```

## 8. List and Loop
This program introduces lists, a basic data structure, and shows how to iterate through its elements using a for loop.

 Iterates through a list of fruits and prints each one
```python
    # A list is a collection of items, stored in a single variable.
    # Items are separated by commas and enclosed in square brackets `[]`.
    fruits = ["Apple", "Banana", "Cherry"]

    # This `for` loop will go through each item in the `fruits` list, one by one.
    # In the first run, `fruit` will be "Apple". In the second, it will be "Banana", and so on.
    for fruit in fruits:
        # Print the current fruit from the list.
        print(f"Current fruit: {fruit}")
```

## 9. Simple Function
This example covers how to define and call a reusable block of code (a function) to perform a specific task, promoting modular and clean code.

 Defines and calls a function to add two numbers
   ```python
    # The `def` keyword is used to define a function. `add_numbers` is the function name.
    # `(a, b)` are the parameters - they are placeholders for the values you'll give the function later.
    def add_numbers(a, b):
        # The `return` keyword sends a value back from the function.
        return a + b

    # Here, we "call" the function with the values 5 and 3.
    # 5 becomes `a` and 3 becomes `b` inside the function.
    # The returned value (8) is stored in the `result` variable.
    result = add_numbers(5, 3)

    # Print the result we got from the function.
    print(f"The function returned: {result}")
```

## 10. String Reversal
A classic "Pythonic" example that demonstrates the power of string slicing to reverse a sequence of characters in a single line of code.

 Reverses a string using slicing
```python
    original_string = "Python"

    # This is called "slicing". The syntax is `[start:stop:step]`.
    # By leaving start and stop blank and using a step of -1, we tell Python
    # to go through the entire string backwards.
    reversed_string = original_string[::-1]

    # Print the newly created reversed string.
    print(f"Reversed string: {reversed_string}")
```

# 🤝 Contributing
Feel free to fork this repo, add more Python programs, and submit a pull request.

# ⭐ Support
If you found this helpful, please star ⭐ the repository to support more projects like this.
