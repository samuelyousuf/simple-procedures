# Write and execute your first Python function

Use this procedure to write and execute your first Python function from a command-line interface (CLI).

1. Open a text editor or integrated development environment (IDE) application.

2. Create a new Python file, and name it `first_function.py`.

3. Type the `def` keywork along with a name surrounded by open and closed parentheses, with a colon at the end.

    ````python
    def main():
    ````

4. In the body of the function, indent your cursor position four spaces. (Typically, this is done automatically by the application you're using.)

5. Type `print("Hello, World!")` in the function body.

    ````python
    def main():
        print("Hello, World!")
    ````

6. Outside of the function space, create a variable named `foo`, and set it to the function name with parentheses.

    ````python
    def main():
        print("Hello, World!")
    
    foo = main()
    ````

7. After the variable, on the next line, type `print(foo)`.

    ````python
        def main():
            print("Hello, World!")
    
        foo = main()

        print(foo)
    ````

8. Save your work.

9. Open a new terminal window, and then type:
    - For Windows users, type `py` and then the name of the Python file.

        ````shellscript
        py first_function.py
        ````

    - For macOS/Linux users, type `python3` and then the name of the Python file.

        ````shellscript
        python3 first_function.py
        ````

10. Press `enter`.

The terminal will return "Hello, World!" (without quotations) to the standard output.

````sh
Hello, World!
````
