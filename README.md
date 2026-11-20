print("==================================================")
print("             PYTHON LEARNING HUB")
print("              INTERACTIVE TUTORIAL")
print("==================================================")

while True:

    print("\n=============== MAIN MENU ===============")

    print("\n[PRELIMINARY LESSONS]")
    print("1. Introduction to Python")
    print("2. Understanding Programming")
    print("3. Python Print Function")
    print("4. Comments in Python")
    print("5. Variables and Data Types")
    print("6. Arithmetic Operators")

    print("\n[MIDTERM LESSONS]")
    print("7. Input Function")
    print("8. F-Strings")
    print("9. Conditional Statements")

    print("\n[FINAL LESSON]")
    print("10. Looping")

    print("\n0. Exit")
    print("==========================================")

    choice = input("\nEnter your choice (0-10): ").strip()

    if choice == "1":

        print("\n--- INTRODUCTION TO PYTHON ---")
        print("Python is a high-level programming language.")
        print("It was created by Guido van Rossum in 1991.")
        print("It is known for its simple and readable syntax.")
        print("Python is used in web development, automation,")
        print("artificial intelligence, and data science.")

        print("\nQUIZ: Who developed Python?")
        print("A. Bill Gates")
        print("B. Guido van Rossum")
        print("C. Mark Zuckerberg")

        answer = input("Your answer: ").strip().lower()

        if answer == "b":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is B.")

    elif choice == "2":

        print("\n--- UNDERSTANDING PROGRAMMING ---")
        print("Programming is the process of writing instructions")
        print("that tell a computer what tasks to perform.")
        print("It helps us create software, applications, and systems.")

        print("\nQUIZ: What is programming?")
        print("A. Giving instructions to a computer")
        print("B. Playing computer games")
        print("C. Browsing the internet")

        answer = input("Your answer: ").strip().lower()

        if answer == "a":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is A.")

    elif choice == "3":

        print("\n--- PYTHON PRINT FUNCTION ---")
        print("The print() function displays information on the screen.")
        print("It can display text, numbers, and variables.")

        print("\nExample:")
        print("print('Welcome to Python!')")
        print("Output: Welcome to Python!")

        print("\nQUIZ: Which function displays output?")
        print("A. input()")
        print("B. print()")
        print("C. int()")

        answer = input("Your answer: ").strip().lower()

        if answer == "b":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is B.")

    elif choice == "4":

        print("\n--- COMMENTS IN PYTHON ---")
        print("Comments are notes written inside the code.")
        print("They help programmers understand the program.")
        print("A single-line comment starts with the # symbol.")

        print("\nExample:")
        print("# This is a Python comment")

        print("\nQUIZ: What symbol starts a single-line comment?")
        print("A. //")
        print("B. &")
        print("C. #")

        answer = input("Your answer: ").strip().lower()

        if answer == "c":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is C.")

    elif choice == "5":

        print("\n--- VARIABLES AND DATA TYPES ---")
        print("A variable stores information or values in a program.")
        print("Python has different types of data.")

        print("\nExamples:")
        print("student = 'David'  # String")
        print("age = 18            # Integer")
        print("grade = 92.5        # Float")
        print("is_enrolled = True  # Boolean")

        print("\nQUIZ: Which data type stores whole numbers?")
        print("A. String")
        print("B. Integer")
        print("C. Float")

        answer = input("Your answer: ").strip().lower()

        if answer == "b":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is B.")

    elif choice == "6":

        print("\n--- ARITHMETIC OPERATORS ---")
        print("Arithmetic operators perform mathematical calculations.")

        print("\nOPERATORS:")
        print("+  Addition")
        print("-  Subtraction")
        print("*  Multiplication")
        print("/  Division")
        print("%  Modulus")
        print("** Exponentiation")
        print("// Floor Division")

        print("\nExample:")
        print("result = 8 * 4")
        print("Output: 32")

        print("\nQUIZ: What is the result of 15 % 4?")
        print("A. 3")
        print("B. 4")
        print("C. 2")

        answer = input("Your answer: ").strip().lower()

        if answer == "a":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is A.")

    elif choice == "7":

        print("\n--- INPUT FUNCTION ---")
        print("The input() function allows users to enter information.")
        print("By default, input() returns a string.")
        print("The int() function converts a value into a whole number.")

        print("\nExample:")
        print("name = input('Enter your name: ')")
        print("age = int(input('Enter your age: '))")

        print("\nQUIZ: Which function gets information from the user?")
        print("A. print()")
        print("B. input()")
        print("C. range()")

        answer = input("Your answer: ").strip().lower()

        if answer == "b":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is B.")

    elif choice == "8":

        print("\n--- F-STRINGS ---")
        print("F-strings allow variables and expressions")
        print("to be inserted directly into a string.")
        print("They use the letter f before the quotation mark.")

        print("\nExample:")
        print("name = 'David'")
        print("print(f'Hello, {name}!')")
        print("Output: Hello, David!")

        print("\nQUIZ: What letter creates an f-string?")
        print("A. s")
        print("B. p")
        print("C. f")

        answer = input("Your answer: ").strip().lower()

        if answer == "c":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is C.")

    elif choice == "9":

        print("\n--- CONDITIONAL STATEMENTS ---")
        print("Conditional statements allow a program to make decisions.")
        print("The main keywords are if, elif, and else.")

        print("\nExample:")
        print("score = 85")
        print("if score >= 75:")
        print("    print('Passed')")
        print("else:")
        print("    print('Failed')")

        print("\nQUIZ: Which keyword checks the first condition?")
        print("A. if")
        print("B. print")
        print("C. input")

        answer = input("Your answer: ").strip().lower()

        if answer == "a":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is A.")

    elif choice == "10":

        print("\n--- LOOPING ---")
        print("Loops repeat a block of instructions.")
        print("Python has two common types of loops: for and while.")

        print("\nFOR LOOP EXAMPLE:")
        print("for number in range(1, 6):")
        print("    print(number)")

        print("\nWHILE LOOP EXAMPLE:")
        print("count = 1")
        print("while count <= 5:")
        print("    print(count)")
        print("    count += 1")

        print("\nQUIZ: Which loop is commonly used to iterate")
        print("through a sequence?")
        print("A. if")
        print("B. for")
        print("C. else")

        answer = input("Your answer: ").strip().lower()

        if answer == "b":
            print("Correct! Well done!")
        else:
            print("Incorrect! The correct answer is B.")

    elif choice == "0":

        print("\n==================================================")
        print("       THANK YOU FOR USING PYTHON LEARNING HUB!")
        print("              KEEP LEARNING!")
        print("==================================================")
        break

    else:

        print("\nInvalid selection!")
        print("Please enter a number from 0 to 10.")
