**Week 1 Java Programs
📌 Overview**

This repository contains Week 1 Java programs focused on basic array operations, searching algorithms, number-based problems, and fundamental logic building using Java.
Each program follows a structured format including Aim, Algorithm, Program, Output, and Result, suitable for academic lab/practical submissions.

**🛠 Requirements**

Java JDK 8 or higher

Any Java IDE (VS Code / IntelliJ / Eclipse / NetBeans)

Command Prompt / Terminal (optional)

**📂 List of Programs**
🔹 Task 1: Access Element in an Array

Accesses and prints an element at a given index

Handles invalid index conditions

🔹 Task 2: Binary Search in Sorted Array

Searches an element using Binary Search technique

Returns index if found, otherwise displays not found

🔹 Task 3: Maximum Element in an Array

Finds the largest element from an integer array

🔹 Task 4: Kth Smallest Element

Sorts the array and finds the Kth smallest element

🔹 Task 5: Print All Possible Pairs in an Array

Generates and prints all unique pairs of array elements

🔹 Task 6: Sum of Digits (Even / Odd Option)

Calculates sum of either even or odd digits based on user choice

🔹 Task 7: Nth Fibonacci Number

Computes the Nth Fibonacci number using iteration

🔹 Task 8: Palindrome Number Check

Checks whether a given number is a palindrome

Returns 2 if palindrome, otherwise 1

🔹 Task 9: Sum of Last Digits

Finds and adds the last digits of two given numbers

Handles negative numbers correctly

**▶ How to Run the Programs**
javac FileName.java
java FileName


**Example:**

javac BinarySearchShort.java
java BinarySearchShort

**✅ Learning Outcomes**

Understanding arrays and loops in Java

Implementing searching and sorting logic

Working with numbers and conditions

Developing problem-solving skills using Java

**author**
Name: (M Thulasiram)
Course: Java Programming
Week: 1


**📌 Overview # PST Java – Week 2**

This repository contains Week 2 Java programs focusing on Java Stream API, String manipulation, Number problems, and Java Date & Time API.
Each task includes Aim, Algorithm, Program, Output, and Result, as required for practical/lab submission.

The programs demonstrate both intermediate and terminal operations in Java along with problem-solving using core Java concepts 

weak 2 pst java

.

**🛠 Requirements**

Java JDK 8 or above

Any Java IDE (VS Code / IntelliJ / Eclipse / NetBeans)

Command Line (optional)

**📂 List of Programs**
🔹 Task 1: Java Stream API – Basic Operations

Uses filter, map, distinct, sorted, forEach

Squares even numbers and finds sum using streams

🔹 Task 2: Stream Intermediate Operations

Demonstrates map, filter, sorted

Filters names and converts them to uppercase

🔹 Task 3: Mini-Max Sum using Streams

Finds minimum and maximum sum from an integer array

🔹 Task 4: Stream Terminal Operations

Uses average, count, and other terminal operations

🔹 Task 5: Palindrome String Check

Checks whether a given string is a palindrome

🔹 Task 6: Digit Count Program

Counts total digits in an integer (including zero and negatives)

🔹 Task 7: Java Date and Time API

Uses LocalDate, LocalTime, LocalDateTime

Formats date and performs date arithmetic

🔹 Task 8: Hill Pattern Weight

Calculates weight of a string based on characters and digits

🔹 Task 9: Zoned Date and Time API

Demonstrates time-zone-based date and time handling

🔹 Task 10: Sum of Sums of Digits

Calculates cyclic sum of digits from a number

**▶ How to Run a Program**
javac FileName.java
java FileName


**Example:**

javac PalindromeString.java
java PalindromeString

**✅ Learning Outcomes**

Understanding Java Stream API

Working with Date & Time APIs

Problem-solving using Java

Writing clean and structured Java programs

**📄 Author**

Name: (M.Thulasiram)
Course: Java Programming
Week: 2


**Week 3 – Java Programming Tasks
 Overview**

This repository contains solutions for Week 3 Java programming tasks, focusing on string manipulation, sorting using comparators, object-oriented programming, and basic algorithmic problem solving. Each task includes its aim, algorithm, Java implementation, and verified output.

The tasks are implemented using core Java concepts such as:

Strings and substrings

Comparator and Collections framework

Classes and objects

Loops and conditional logic

📄 Source: Week-3 Assignment PDF 

**week3**

**Technologies Used**

Language: Java

Concepts: OOP, Comparator, Collections, Algorithms

Tools: JDK, Scanner class

 **Tasks Included**
**Task 1:** Lexicographically Smallest and Largest Substrings

Aim:
Find the smallest and largest substrings of length k from a given string using lexicographical comparison.

Key Concepts:
String manipulation, compareTo() method

**Task 2:** Player Ranking Using Comparator

Aim:
Sort Player objects:

Descending order of score

Ascending alphabetical order of name if scores are equal

Key Concepts:
Custom Comparator, object sorting

**Task 3:** Student Sorting by CGPA

Aim:
Sort students based on:

CGPA (descending)

First name (ascending)

ID (ascending)

Key Concepts:
Collections framework, multi-level sorting

**Task 4:** Sort People by Height

Aim:
Sort people’s names based on their heights in descending order.

Key Concepts:
Array manipulation, Bubble Sort logic

**Task 6:** Nth Prime Number

Aim:
Find the Nth prime number using a helper method to check primality.

Key Concepts:
Loops, prime number logic, helper methods

**Task 8:** Lexicographical Substring Comparison

Aim:
Identify smallest and largest substrings of length k from a string.

Key Concepts:
String slicing, lexicographical comparison

**Task 9:** Addition and Subtraction Pattern

Aim:
Compute a result by performing addition and subtraction from N to 1 based on a selected option.

**Key Concepts:**
Conditional logic, iteration, pattern-based computation

 **Output Status**
All programs were successfully executed, and outputs were verified using sample test cases as shown in the assignment document.

**How to Run**

**Compile the Java file:**

javac FileName.java

**Run the program:**

java FileName


Provide input as prompted.

**Conclusion**

This assignment demonstrates effective use of Java fundamentals and problem-solving techniques. It strengthens understanding of sorting mechanisms, string operations, and logical computation.

 **WEEK 4 – Java Programming Tasks**

This repository contains solutions to 10 programming tasks implemented in Java.
Each task includes:

 Aim

 Algorithm

 Program

 Output

 Result

 **TASK 1 – Halves Are Alike**

Aim:
Determine whether both halves of an even-length string contain the same number of vowels.

Concept Used: String traversal, vowel counting

Key Idea:
Split string into two halves → Count vowels → Compare counts

**TASK 2 – Lapindrome Check**

Aim:
Check whether a given string is a lapindrome.

Concept Used: Frequency array (26 characters)

Key Idea:
Split string → Ignore middle character if odd length → Compare frequency arrays

**TASK 3 – Compare Triplets**

Aim:
Compare two triplets and calculate scores.

Concept Used: Element-wise comparison

Scoring Rule:

If a[i] > b[i] → scoreA++

If a[i] < b[i] → scoreB++

 **TASK 4 – Contains Duplicate**

Aim:
Check whether an integer array contains duplicate elements.

Concept Used: HashSet

Key Idea:
If element already exists in set → return true
Else → add to set

**TASK 5 – Time Conversion**

Aim:
Convert 12-hour AM/PM time format to 24-hour format.

Concept Used: String manipulation

Special Cases:

12:XX:XX AM → 00:XX:XX

12:XX:XX PM → 12:XX:XX

**TASK 6 – Move Zeroes**

Aim:
Move all zero elements to the end while maintaining order.

Concept Used: Two-pointer technique

Time Complexity: O(n)

 **TASK 7 – Diagonal Difference**

Aim:
Find absolute difference between primary and secondary diagonal sums.

Formula:

Primary → arr[i][i]

Secondary → arr[i][n-i-1]

Time Complexity: O(n)

**TASK 8 – Matrix Transpose**

Aim:
Transpose a matrix (convert rows into columns).

Formula:

result[j][i] = matrix[i][j]


Time Complexity: O(m × n)

**TASK 9 – Matrix Block Sum**

Aim:
Compute block sum for each element within distance k.

Concept Used: 2D Prefix Sum

Optimization:
Block sum calculated in O(1) using prefix matrix.

Total Complexity: O(m × n)

**TASK 10 – Matrix Rotation**

Aim:
Rotate matrix anticlockwise by r rotations layer by layer.

Concept Used: Layer-by-layer traversal

Steps:

Extract layer elements

Rotate list using modulo

Place elements back

Time Complexity: O(m × n)

**Technologies Used**

Java

Arrays

Strings

HashSet

Lists

2D Matrices

Prefix Sum Technique

 **Learning Outcomes**

After completing these tasks, you understand:

String processing techniques

Frequency counting

Hashing

Two-pointer methods

Matrix traversal

Prefix sum optimization

Layer-based matrix rotation

Time complexity analysis

 **Conclusion**

All 10 tasks were successfully implemented and tested.
The programs execute correctly and produce expected outputs as shown in the document 
