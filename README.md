
# C# Console Application - Person Management System
 

## Description:
This C# console application is designed to manage information about individuals, including their name, age, height, and gender. The core of the program revolves around a class called Person, which represents these details and features methods to calculate the ideal weight based on height and gender.

## Person Class
The Person class has the following private attributes:

**name:** Person's name.
**age:** Person's age.
**height:** Person's height.
**gender:** Person's gender.
It includes two constructors, one without parameters and another with parameters to initialize the class attributes.

The calculateIdealWeight method calculates the ideal weight based on the person's height and gender, using different formulas for men and women.

The overridden ToString method generates a string representation of the person's data.

**Main Program ( Program Class)**

The main program features a simple menu allowing users to perform the following operations:
- Add Person: Allows the user to input information about an individual.
- List All People: Displays data for all registered individuals.
- Average Ideal Weight for Men: Calculates and displays the average ideal weight for individuals identified as male.
- Average Ideal Weight for Women: Calculates and displays the average ideal weight for individuals identified as female.
- Exit: Ends the program.

The code employs an array of Person class objects to store the information of registered individuals.

The menu method displays the menu options and returns the user's choice.

The addPerson method prompts the user for information to create a new instance of the Person class.

The listPeople method displays data for all registered individuals.

The displayAverageIdealWeight method calculates and displays the average ideal weight based on the provided gender.

The program continues running until the user chooses the "0" option to exit.

## Usage:


- Clone the repository.

- Open the project in a C# IDE.

- Run the program and follow the on-screen instructions.

- Feel free to contribute or provide feedback!


## Author
- [@Carlos Martins](https://github.com/MartinsCarlos111)

