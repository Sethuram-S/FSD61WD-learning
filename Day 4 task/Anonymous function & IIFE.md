<h3>1. Print Odd Numbers in an Array:</h3>

- <b>I start with an array of numbers:</b> var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];
- <b>An anonymous function (IIFE) is used to filter out odd numbers from the array:</b> (() => { ... })();
- <b>Inside the function, I use filter to create a new array containing only the odd numbers:</b> var oddNumbers = numbers.filter(num => num % 2 !== 0);
- Finally, I log the oddNumbers array to the console.

<h3>2. Convert All Strings to Title Case in a String Array:</h3>

- <b>I have an array of strings:</b> var stringArray = ["html", "CSS", "javascript", "is", "Fun"];
- <b>Again, an anonymous function is used to transform each string to title case:</b> (() => { ... })();
- <b>I use map to create a new array with title-cased strings:</b> var titleCaseArray = stringArray.map(str => str.charAt(0).toUpperCase() + str.slice(1));
- The resulting titleCaseArray is logged to the console.

<h3>3. Sum of All Numbers in an Array:</h3>

- <b>I have an array of numbers:</b> var nums = [10, 20, 30, 40, 50];
- <b>The IIFE calculates the sum of all numbers using reduce:</b> var sum = nums.reduce((acc, curr) => acc + curr, 0);
- The sum is then logged to the console.

<h3>4. Return All Prime Numbers in an Array:</h3>

- <b>I start with an array of numbers:</b> [2, 3, 5, 7, 10, 11, 13].
- The function isPrime checks if a number is prime.
- It starts by assuming the number is prime.
- Then it checks if the number is divisible evenly by any smaller number (from 2 up to num - 1).
- If it finds any such divisor, it concludes that the number is not prime. Otherwise, it confirms that the number is prime.
- I use the filter method on the array of numbers.
- It applies the isPrime function to each number.
- If the function returns true, the number is included in the new array of prime numbers.
- The final array contains only the prime numbers from the original array.

<h3>5. Return All Palindromes in an Array:</h3>

- <b>I have an array of words:</b> var words = ["level", "hello", "madam", "world"];
- The IIFE defines a function isPalindrome that checks if a word is a palindrome.
- It uses filter to create a new array containing only palindromes: var palindromes = words.filter(isPalindrome);
- The palindromes are logged to the console.

<h3>6. Return Median of Two Sorted Arrays of the Same Size:</h3>

- <b>I have two sorted arrays:</b> var arr1 = [1, 3, 5]; and var arr2 = [2, 4, 6];
- The IIFE merges the arrays and calculates the median:

    <b>Merge:</b> var mergedArray = [...arr1, ...arr2].sort((a, b) => a - b);

    <b>Calculate median:</b> var median = mergedArray.length % 2 === 0 ? (mergedArray[middleIndex - 1] + mergedArray[middleIndex]) / 2 : mergedArray[middleIndex];
- The median value is logged to the console.

<h3>7. Remove Duplicates from an Array:</h3>

- <b>I have an array with duplicates:</b> var duplicateArray = [1, 2, 2, 3, 4, 4, 5];
- <b>The IIFE creates a new array with unique elements using Set:</b> var uniqueArray = [...new Set(duplicateArray)];
- The uniqueArray is logged to the console.

<h3>8. Rotate an Array by k Times:</h3>

- <b>I have an original array:</b> var originalArray = [1, 2, 3, 4, 5];
- <b>The IIFE rotates the array by k positions:</b> var rotatedArray = [...originalArray.slice(k), ...originalArray.slice(0, k)];
- The rotatedArray is logged to the console.