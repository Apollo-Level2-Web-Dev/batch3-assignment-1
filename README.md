# batch3-assignment-1

## Assignment: Basic Problem Solving with TypeScript

This assignment comprises various problems that demonstrate fundamental TypeScript concepts, including data typing, interfaces for objects, class usage with inheritance, type checking, and manipulation of data structures. The solutions aim to showcase efficient and clear problem-solving techniques using TypeScript, adhering to best coding practices.

The assignment tasks cover a range of topics:

1. *String Manipulation:* Implementing functions to repeat strings and reverse arrays.
2. *Array Operations:* Finding the largest number in an array and filtering even numbers.
3. *Object Handling:* Defining interfaces for student and book objects and performing operations like calculating average grades and checking recent book publications.
4. *Type Guard and Error Handling:* Creating a function to log strings and handle different data types using type guards.
5. *Class Implementation:* Designing a class to represent car information and displaying relevant details.

Each problem is accompanied by sample input and output, showcasing how TypeScript can be used to solve practical programming challenges effectively.If you have any questions or need further clarification on any problem, please let us know in our facebook group.

## Problem 1:

Design a TypeScript function `repeatString` that takes two parameters: a string and a number. The function should return a new string that repeats the input string the specified number of times.

```tsx
// Sample Input: 
repeatString("Hello!", 3)

// Sample Output:
"Hello!Hello!Hello!"
```

## Problem 2:

Design a TypeScript function `findLargestNumber` that takes an array of numbers and returns the largest number in the array.

```tsx
// Sample Input:
findLargestNumber([10, 5, 8, 20, 3])

// Sample Output:
20
```

## Problem 3:

Create a TypeScript function `filterEvenNumbers` that takes an array of numbers and returns a new array containing only the even numbers from the original array.

```tsx
// Sample Input:
filterEvenNumbers([1, 2, 3, 4, 5, 6])

// Sample Output:
[2, 4, 6]
```

## Problem 4:

Design a TypeScript function `reverseArray` that takes an array of any type and returns a new array with its elements reversed. Use generics to define types.

```tsx
// Sample Input 1:
reverseArray(["apple", "banana", "cherry"])

// Sample Output 1:
["cherry", "banana", "apple"]

// Sample Input 2:
reverseArray([10, 20, 30])

// Sample Output 2: 
[30, 20, 10]
```

## Problem 5:

You are given an object called “student”  representing a student's information with the following properties: name (string), age (number), and grades (array of numbers). Make an interface using given properties. Write a TypeScript function called `calculateAverageGrade` that takes this student object as input and calculates the average grade.

> Hints: Use a `reduce()` method to sum the grades. average = total grades/ total length
> 

```tsx
// Sample Input:
const student1: Student = {     
			    name: "Bob",     
			    age: 17,     
			    grades: [75, 80, 82, 88, 90]
                       };


const averageGradeForBob = calculateAverageGrade(student1);

// Sample Output:
83
```

## Problem 6:

You are given an object representing a book with properties title (string), author (string), and publishedYear (number). Use type alias for declaring the object.
Write a TypeScript function called `isRecentBook` that takes this book object as input and determines if the book was published in the last 5 years.

> Hints: Use `getFullYear()` method to extract the year to check the given year with current year.
> 

```tsx
// Sample Input :
const book1: Book = {
    title: "Sample Book",
    author: "John Doe",
    publishedYear: 2022
};
isRecentBook(book1);

// Sample Output: 
true
```

## Problem 7:

Create a TypeScript function `logString` that takes a parameter of type unknown and uses a type guard to check whether the parameter is of type string. If it is, log the string to the console. If it is not, log an error message.

```tsx
// Sample Input 1: 
logString("Hello, TypeScript!");

// Sample Output 1:  
"Hello, TypeScript!"

// Sample Input 2: 
logString(42)

// Output: Error: 
Input is not a string.
```

## Problem 8:

Design a TypeScript class Car that represents a basic car with properties for brand, model, and year. Implement a method displayInfo that displays information about the car.

```tsx
// Sample Input:
new Car("Toyota", "Corolla", 2020);

// Sample Output: 
"Your car model is:  2020 Toyota Corolla"
```

</br>
</br>
</br>

## Blog Writing (anyone):

Write an impactful blog posts covering the following topics:
1. The significance of union and intersection types in Typescript.
2. How to handle asynchronous operations using `async/await` over `callback/promise` TypeScript.
3. Why are Type Guards Necessary? Discuss Various Types of Type Guards and Their Use Cases.

</br>
</br>
</br>

## Private Repogitory
[https://classroom.github.com/a/xLyOULhz](https://classroom.github.com/a/xLyOULhz)

### Instructions:
* Solve the problems in a separate file. Name the file starting with "problem-" followed by the problem number.
   (For example: problem-1.ts)
* Write the blogs in separate .md files. Name them starting with "blog-" followed by the blog number.
  (For example: blog-1.md / blog-2.md)
* The blog should be written in simple English, providing some code examples.
* Make sure the solution you provide is your own work and doesn't use any AI or machine-generated help. Stick to the rules given.
* Follow standard coding practices to make your code easy to read and understand.
* Don't copy code from other students. If you do, you'll get a score of 0.
* Share the link to your GitHub repository where you've uploaded your submission.

### Assignment Deadlines:

- 60 marks: May 8, 2024, 11:59 PM
- 50 marks: May 9, 2024, 11:59 PM
- 30 marks: After May 9, 11.59 PM
