# CGPA Calculator (C++)

This project is a simple C++ program designed to calculate the Cumulative Grade Point Average (CGPA) for a student based on their grades in various subjects. The program accepts the number of subjects, their credit hours, and the grade obtained in each subject. It then computes the weighted average to determine the CGPA.

## Features

- Input for the number of subjects, credit hours, and grades.
- Weighted average calculation based on credit hours.
- Displays the final CGPA.
- Option to handle grades in a user-friendly format (e.g., A, B+, C, etc.).

## Requirements

- C++ compiler (e.g., GCC, Clang, or MSVC)
- C++11 or later standard.

## How to Use

1. Clone or download the repository.

    ```bash
    git clone https://github.com/yourusername/cgpa-calculator.git
    ```

2. Navigate to the project directory.

    ```bash
    cd cgpa-calculator
    ```

3. Compile the code using a C++ compiler.

    ```bash
    g++ -o cgpa_calculator main.cpp
    ```

4. Run the program.

    ```bash
    ./cgpa_calculator
    ```

5. Follow the on-screen prompts to input the number of subjects, credit hours, and corresponding grades.

6. The program will output the calculated CGPA based on the inputs.

## Example

Here's an example of how the program works:

```bash
Enter the number of subjects: 3
Enter the details for each subject:

Subject 1:
Enter the grade (A, B+, C, etc.): A
Enter the credit hours: 3

Subject 2:
Enter the grade (A, B+, C, etc.): B+
Enter the credit hours: 4

Subject 3:
Enter the grade (A, B+, C, etc.): B
Enter the credit hours: 3

Your CGPA is: 3.45
