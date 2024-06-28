<h3>1. Print Odd Numbers in an Array:</h3>

- I start with an array of numbers: [1, 2, 3, 4, 5, 6, 7, 8, 9].
- The arrow function filters out odd numbers: var oddNumbers = numbers.filter(num => num % 2 !== 0);
- It checks if the remainder after dividing each number by 2 is not equal to 0.
- The oddNumbers array contains only the odd numbers.

<h3>2. Convert All Strings to Title Caps in a String Array:</h3>

- I have an array of strings: ["i am", "new to", "javascript"].
- The arrow function maps each string to title case: var titleCaseArray = stringArray.map(str => str.charAt(0).toUpperCase() + str.slice(1));
- It capitalizes the first letter of each string and combines it with the rest of the string.
- The resulting titleCaseArray contains title-cased strings.

<h3>3. Sum of All Numbers in an Array:</h3>

- I have an array of numbers: [10, 20, 30, 40, 50].
- The arrow function calculates the sum using reduce: var sum = nums.reduce((acc, curr) => acc + curr, 0);
- It starts with an initial value of 0 (acc) and adds each number (curr) to it.
- The sum variable holds the total sum.

<h3>4. Return All Prime Numbers in an Array:</h3>

- I have an array of numbers to check: [2, 3, 5, 7, 10, 11, 13].
- The arrow function defines isPrime, which checks if a number is prime.
- It iterates from 2 up to the number itself, looking for divisors.
- If no divisors are found, the number is considered prime.
- The resulting primeNumbers array contains only prime numbers.

<h3>5. Return All Palindromes in an Array:</h3>

- I have an array of words: ["level", "hello", "madam", "world"].
- The arrow function defines isPalindrome, which checks if a word reads the same backward.
- It compares the original word with its reversed version.
- The palindromes array contains only palindromic words.