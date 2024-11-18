
# Advanced Java Programming Assessment

## Total Time: 50 minutes
## Total Marks: 50

---

### Section A: Multiple Choice Questions (2 marks each)

1. What is the result of the following code snippet?
   ```java
   int x = 10, y = 20;
   if (x < y && x + y > 25) {
       System.out.println("Condition met");
   }
   ```
   a) Condition met  
   b) Compilation Error  
   c) Runtime Error  
   d) No output  

2. Which of the following is NOT a valid array declaration in Java?  
   a) `int[] numbers = new int[5];`  
   b) `int numbers[] = {1, 2, 3};`  
   c) `int numbers[5];`  
   d) `int[] numbers; numbers = new int[5];`  

3. What does the `Math.max()` method do?  
   a) Finds the largest element in an array  
   b) Returns the greater of two numbers  
   c) Finds the maximum possible value of an integer  
   d) Compares two arrays  

4. What is printed by the following code?  
   ```java
   String str = "Hello, World!";
   System.out.println(str.substring(7, 12));
   ```  
   a) World  
   b) Hello  
   c) , Wo  
   d) , Wor  

5. Which loop would you use if you know the exact number of iterations required?  
   a) `while`  
   b) `do-while`  
   c) `for`  
   d) Any of the above  

---

### Section B: Short Answer Questions (5 marks each)

1. Write a Java program to input a student's marks in five subjects and calculate the average. If the average is 50 or more, output "Pass"; otherwise, output "Fail."

2. Explain the difference between `break` and `continue` statements in loops. Provide an example for each.

3. Write a Java program that reads a sentence from the user and outputs the number of vowels in the sentence.

4. What is the output of the following program? Justify your answer:
   ```java
   int[] arr = {10, 20, 30, 40, 50};
   int sum = 0;
   for (int i = 0; i < arr.length; i++) {
       if (arr[i] % 20 == 0) continue;
       sum += arr[i];
   }
   System.out.println(sum);
   ```

---

### Section C: Problem-Solving Tasks (10 marks each)

1. **Array Manipulation Task**  
   Write a Java program that:  
   - Stores the names, ages, and points of 5 players in three parallel arrays.  
   - Finds the youngest player and displays their details.  
   - Calculates and prints the average points scored by all players.

2. **String Manipulation and Methods Task**  
   Write a Java program that:  
   - Accepts a string from the user.  
   - Checks whether the string is a palindrome (reads the same forward and backward).  
   - Uses a separate method to perform the palindrome check.

---

### Section D: Challenge Task (Bonus 10 Marks)

Write a Java program to simulate a simple inventory management system:  
- Store the names and quantities of 5 items in two parallel arrays.  
- Provide the user with options to:  
  1. Add new stock to an item.  
  2. Remove stock from an item (ensure quantity does not go below zero).  
  3. Display all items and their quantities.  
- Use a `switch` statement to handle the options.

---


