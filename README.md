# cgpacalculator



# Features

- Calculate CGPA from course grades and credits.
- Save course details and CGPA to a text file.
- Simple and easy-to-use console application.

# Usage

1. Clone or download this repository to your local machine.
   bash
   https://github.com/jeripothulasiri/cgpacalculator


3. Navigate to the project directory.
   bash
   cd Cgpa-Calculator

4. Compile the C++ program.

   bash
   g++ cgpa_calculator.cpp -o cgpa_calculator

5. Run the program.

   bash
   ./cgpa_calculator
   

6. Follow the on-screen prompts to enter course details (credits and grades) as required.

7. The program will calculate your CGPA and display it on the console. Additionally, the course details and CGPA will be saved to a file named `cgpa_data.txt`.

# Output
Certainly! Let's walk through the detailed output explanation for the CGPA Calculator program. I'll explain each part of the output and what it means.

Let's assume the user has entered information for three courses:

Enter the number of courses: 3

For each course, they have entered credits and grades. Here's an example input:

Enter credits for course 1: 3
Enter grade for course 1: 4.0
Enter credits for course 2: 4
Enter grade for course 2: 3.5
Enter credits for course 3: 2
Enter grade for course 3: 3.7

Now, if you open the `cgpa_data.txt` file, it will contain the following information:

Course 1: Credits = 3, Grade = 4.0
Course 2: Credits = 4, Grade = 3.5
Course 3: Credits = 2, Grade = 3.7
CGPA: 3.61



