# Lab: 7.0.2

**Objective:**

- Understand the concept and importance of Writing Methods in Java development. 
- Learn how to implement methods using Java syntax and best practices. 
- Explore practical applications of methods in real-world Java projects. 
- Identify common pitfalls and best practices when working with methods. 
- Gain hands-on experience with a complete Java example that demonstrates method writing and usage.

**Prerequisites:**

- Basic understanding of Java programming. 
- Familiarity with variables, data types, and basic control structures in Java.

**What You'll Achieve:**

- Develop a solid understanding of method declaration and invocation in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in code organization and reusability.

**Assignment Details**

In this assignment, you will create a `TemperatureConverter` class with the following methods:

1. `celsiusToFahrenheit`: Converts Celsius to Fahrenheit.
2. `fahrenheitToCelsius`: Converts Fahrenheit to Celsius.
3. `roundToTwoDecimalPlaces`: Rounds a double to two decimal places.

In the `main` method:

1. Prompt the user to enter a temperature value and its unit (C or F).
2. Convert the temperature to the other unit using the appropriate method.
3. Round both the original and converted temperatures to two decimal places.
4. Display the original temperature and its conversion.

**Example Output**

```
Enter a temperature value: 25.5678
Enter the temperature unit (C or F): C

25.57°C is equal to 78.02°F

Enter a temperature value: 98.6543
Enter the temperature unit (C or F): F

98.65°F is equal to 37.03°C
```

**Starter Code**

The `TemperatureConverter.java` file contains the following starter code:

```java
package academy.javapro.lab;

import java.util.Scanner;

public class TemperatureConverter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // TODO: Implement user input and method calls here

        scanner.close();
    }

    // TODO: Implement the required methods here
}

```

**Hints**

- Use the following formulas for temperature conversion:
  - C to F: (C * 9/5) + 32
  - F to C: (F - 32) * 5/9
- For rounding to two decimal places, you can use `Math.round(value * 100.0) / 100.0`
- Remember to handle potential input errors, such as invalid temperature units.
- Use meaningful variable names and add comments to explain your code.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required methods in the `TemperatureConverter.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.