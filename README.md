# Code Generation for Simple Straight Line Programs

The goal of this project is to introduce you to code generation for simple straight line programs without branching. In this project, you will write a C++ program that reads an input program (a sequence of assignments) written in a small programming language defined specifically for this project. Your program will then generate an intermediate code based on the input.

## Project Tasks

There are three main tasks in this project:

1. **Task 1 (90 points):** Parse the input and print an abstract syntax tree.
2. **Task 2 (30 points):** Parse the input and perform type checking.
3. **Task 3 (25 points):** Generate an executable representation of the program. This involves breaking down large expressions into smaller ones that are linked together in a linked list. The linked list is then passed to the "execute" function provided, which must not be modified.

## Instructions

1. Clone the repository to your local machine:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd code-generation-project
    ```

3. Compile the C++ program:

    ```bash
    g++ -o code_generator code_generator.cpp
    ```

4. Run the program with a command-line argument to specify the task:

    ```bash
    ./code_generator <task-number>
    ```

   Replace `<task-number>` with the number of the task you want to execute (1, 2, or 3).

## Example Usage

To execute Task 1 (printing an abstract syntax tree):

```bash
./code_generator 1
To execute Task 2 (performing type checking):

bash
Copy code
./code_generator 2
To execute Task 3 (generating an executable representation):

bash
Copy code
./code_generator 3
```
## Important Note

Ensure that you understand the requirements and constraints of each task before executing the program. Follow the provided instructions carefully to achieve the desired functionality.

For Task 3, pay special attention to breaking down large expressions and linking them together in the appropriate format for the provided "execute" function.

## Contributions

Please feel free to contribute by submitting bug fixes, feature requests, or improvements via pull requests. We appreciate your support in making this project better.
