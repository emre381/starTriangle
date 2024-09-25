
---

# Star Triangle (Baklava Dilimi)

## Description

The Star Triangle program is a simple C# console application that prints a star-shaped triangle (also known as a baklava dilimi) based on user input. The triangle pattern is centered and expands outward in a diamond shape. If the user inputs an even number of rows, the program automatically increments it to the next odd number to maintain symmetry.

## Features

- Prompts the user to enter the number of rows for the star triangle.
- Automatically adjusts even input to the next odd number for symmetry.
- Prints the star triangle to the console, centered.

## Requirements

- .NET SDK (Core or Framework) installed on your machine to run the application.

## Usage

1. Clone or download this repository to your local machine.
2. Open the project in your favorite C# IDE (like Visual Studio or Visual Studio Code).
3. Build the project.
4. Run the application. 
5. When prompted, enter the desired number of rows for the star triangle.
6. The program will display the star triangle in the console.

## Example

If the user inputs `5`, the output will look like this:

```
    *
   ***
  *****
 *******
*********
```

If the user inputs `4`, the program will adjust the input to `5` and print the same triangle as above.

## Code Explanation

- **Main Method**: The entry point of the application where user input is captured.
- **Variables**:
  - `bosluk`: Represents the number of spaces before the stars to center the triangle.
  - `satir`: The number of rows for the triangle, input by the user.
  - `yildiz`: The number of stars to print in the current row.
- **Loops**:
  - The outer loop iterates through each row.
  - The first inner loop prints the spaces.
  - The second inner loop prints the stars.
- **Conditional Logic**: Adjusts the number of spaces and stars based on whether the current row is in the first half or the second half of the triangle.

## License

This project is open-source and available under the MIT License.

---

