# 2.5-Triangle-Identification

#### Objective:
In this assignment, you will write a Python script that determines whether three given lengths can form a triangle. If the lengths do form a triangle, the script will identify the type of triangle: Equilateral, Isosceles, Right Isosceles, Scalene, or Right Scalene.

#### Instructions:

1. **Part 1: Input Lengths**
   - Prompt the user to input three positive numbers representing the lengths of the sides of a potential triangle.
   - Ensure that the input values are valid positive numbers.

2. **Part 2: Determine if the Lengths Form a Triangle**
   - Implement logic to check if the three lengths can form a triangle. Remember the triangle inequality theorem: the sum of the lengths of any two sides must be greater than the length of the third side.
   - If the lengths do not satisfy this condition, print a message indicating that they cannot form a triangle and end the program.

3. **Part 3: Determine the Type of Triangle**
   - If the lengths do form a triangle, determine the type of triangle:
     - **Equilateral Triangle:** All three sides are equal.
     - **Isosceles Triangle:** Two sides are equal, and the third is different.
     - **Right Isosceles Triangle:** Two sides are equal, and the triangle satisfies the Pythagorean theorem (a² + b² = c²), where c is the longest side.
     - **Scalene Triangle:** All three sides are different.
     - **Right Scalene Triangle:** All three sides are different, and the triangle satisfies the Pythagorean theorem.

4. **Part 4: Output the Result**
   - Print the type of triangle formed by the three lengths. If it is a right triangle, specify whether it is a Right Isosceles or a Right Scalene Triangle.

#### Example Output:

- Input: `5, 5, 5`
  - Output: "The lengths form an Equilateral Triangle."

- Input: `3, 3, 4.242640687`
  - Output: "The lengths form a Right Isosceles Triangle."

- Input: `3, 4, 5`
  - Output: "The lengths form a Right Scalene Triangle."

- Input: `7, 7, 10`
  - Output: "The lengths form an Isosceles Triangle."

- Input: `2, 3, 4`
  - Output: "The lengths form a Scalene Triangle."

- Input: `1, 2, 3`
  - Output: "The lengths do not form a triangle."

