# Top 50 Java Programs from Coding Interviews

**1. Fibonacci series** (solution)
Write a simple Java program which will print Fibonacci series, e.g. 1 1 2 3 5 8 13 .... up to a
given number. We prepare for cross questions like using iteration over recursion and
how to optimize the solution using caching and memoization.

**2. A prime number** (solution)
Write a Java program to check if a given number is prime or not. Remember, a prime
number is a number which is not divisible by any other number, e.g. 3, 5, 7, 11, 13, 17,
etc. Be prepared for cross, e.g. checking till the square root of a number, etc.


**3. String Palindrome** (solution)
You need to write a simple Java program to check if a given String is palindrome or not. A
Palindrome is a String which is equal to the reverse of itself, e.g., "Bob" is a palindrome
because of the reverse of "Bob" is also "Bob." Though be prepared with both recursive
and iterative solution of this problem. The interviewer may ask you to solve without
using any library method, e.g. indexOf() or subString() so be prepared for that.

**4. Integer Palindrome** (solution)
This is generally asked as follow-up or alternative of the previous program. This time you
need to check if given Integer is palindrome or not. An integer is called palindrome if it's
equal to its reverse, e.g. 1001 is a palindrome, but 1234 is not because the reverse of
1234 is 4321 which is not equal to 1234. You can use divide by 10 to reduce the number
and modulus 10 to get the last digit. This trick is used to solve this problem.

**5. Armstrong number** (solution)
A number is called an Armstrong number if it is equal to the cube of its every digit. For
example, 153 is an Armstrong number because of 153= 1+ 125+27, which is equal to
1^3+5^3+3^3. You need to write a program to check if the given number is Armstrong
number or not.

**6. Avoiding deadlock in Java** (solution)
This is one of the interesting programs from Java Interviews, mostly asked to 2 to 3 years
of experienced programmers or higher. The interviewer simply asked you to write code
where a resource is accessed by multiple threads. You need to write code in such a way
that no deadlock should occur. The trick to solving this problem is acquiring resources in
order and release them in reverse order, e.g. first acquire resource R1 and only if you
have got R1 to go for R2. This way, you can avoid deadlock.

**7. Factorial** (solution)
This is one of the simplest programs you can expect in interviews. It is generally asked to
see if you can code or not. Sometimes interviewer may also ask about changing a
recursive solution to iterative one or vice-versa.

**8. Reverse a String** (solution)
This problem is similar to the String Palindrome problem we have discussed above. If
you can solve that problem, you can solve this as well. You can use indexOf() or
substring() to reverse a String or alternatively, convert the problem to reverse an array by
operating on character array instead of String. If you want to brush up your data
structure skill you can also check Data Structures and Algorithms: Deep Dive Using
Java course on Udemy before solving this question.

**9. Remove duplicates from an array** (solution)
Write a program to remove duplicates from an array in Java without using the Java
Collection API. The array can be an array of String, Integer or Character, your solution
should be independent of the type of array. If you want to practice more array-based
questions, then see this list of top 30 array interview questions from Java interviews.


10. Printing patterns (solutions)
11. Print repeated characters of String? (solution)
12. GCD of two numbers (solution)
**13. The square root of a number** (solution)
You need to write a program to calculate the square root of a number without using the
Math.sqrt() function of JDK. You need to write your logic and method to calculate the
square root. You can though use the popular algorithm, like Newton's method.
14. Reverse array in place (solution)
15. Reverse words of a sentence (solution)
16. Leap year (solution)
17. Binary search (solution)
**18. String Anagram** (solution)
Write a program to check if two given String is Anagram of each other. Your function
should return true if two Strings are Anagram, false otherwise. A string is said to be an
anagram if it contains the same characters and same length, but in a different order, e.g.
army and Mary are anagrams. You can ignore cases for this problem, but you should
clarify that from your interview.
**19. Design a Vending Machine** (solution)
This one of the popular OOAD (object-oriented analysis and design) question from Java
Interviews. You will be given 3 hours to design and code a vending machine satisfying
some of the business requirements. You also need to write unit tests to prove your code
satisfy those requirements. You can see this article for more object-oriented analysis
questions.
20. Reverse a number (solution)
21. The first non-repeated character of String (solution)
22. Finding Middle element of linked list in one pass (solution)
23. Pre-order traversal (solution)
24. Pre-order traversal without recursion (solution)
25. In order traversal (solution)
26. In order traversal without recursion (solution)
27. Post-order traversal (solution)


28. Postorder traversal without recursion (solution)
29. Print all leaves of a binary tree (solution)
**30. Sort array using quicksort** (solution)
You need to write a Java program to sort an array of integers using a quick sort algorithm.
You cannot use any library method, e.g. JDK or a third party library, which means, you
need to first implement the quicksort algorithm and then sort the array.
**31. Insertion sort** (solution)
Write a program to implement the insertion sort algorithm in Java. The program should
take an unsorted array and sort it using insertion sort algorithm Also explain the best
case and worst case time and space complexity of the Insertion sort algorithm.
**32. Bubble sort** (solution)
Write a program to implement the bubble sort algorithm in Java. You can use basic
operators and functions, but sorting functions from Java API is not allowed.
33. Transpose a matrix (solution)

(solution)
Write a Java program to print all permutations of a given String. For example, if given
String is "GOD" then your program should print all 6 permutations of this string, e.g.
"GOD," "OGD," "DOG," "GDO," "ODG," and "DGO."

35. Reverse a String in place (solution)
36. Adding two matrices in Java (solution)
37. Matrix multiplication (solution)


38. Removal all white space from String (solution)
**39. Reverse a linked list** (solution)
Write a program to reverse a singly linked list in Java. You can use iteration and recursion
to solve this problem, but you should reverse a linked list in place.
**40. Find the length of the linked list** (solution)
Just write a program in Java to find the length of a singly linked list in one pass, i.e. in just
one iteration of a singly linked list.
**41. Check if a linked list has a loop** (solution)
Write a program to check if given linked list has a loop or not. Sometimes a linked list get
corrupt, and two nodes point to the same node, which forms the loop or cycle in the
linked list.
42. Find the start of loop in a linked list (solution)
43. Find the middle element of a linked list (solution)
**44. Find the 3rd element from the tail linked list (** solution)
You need to write a program to find the 3rd element from the tail of a singly linked list.
You need to solve this problem without iterating twice. If you want more linked list
questions, you can see the article about frequently asked linked list interview questions.


**44. Convert a linked list to a binary tree** (solution)
It's possible to convert a doubly-linked list to a binary tree, you need to write a Java
program which takes a doubly-linked list and returns a binary tree.
**45. Sort a linked list** (solution)
You need to given an unsorted linked list, and you need to write a program in Java to sort
them in ascending order of the values in each node.
**46. Iterative Quicksort** (solution)
You need to write a Java program to implement quicksort sorting algorithm without
recursion. You can use essential JDK classes and programming constructs, but recursion
is not allowed.
**46. Bucket sort** (solution)
This program is increasingly getting popular on Java interview because it sorts a given
array in linear time. Though there is a lot of prerequisites, e.g. you must know the
maximum value present in the array, it is a very interesting problem from interview point
of view. You need to write a program to implement a bucket sort algorithm in Java. If you
are not familiar with Bucket sort or any other linear sorting algorithm, I suggest you to
first read a good on algorithms, e.g. Introduction to Algorithms by Thomas H. Cormen.
**47. Counting sort** (solution)
This is another problem which is similar to the previous one because counting sort is
also a linear sorting algorithm. Just remember that bucket sort, and counting sort are
different algorithms, so it's also good to state how they are different.
**48. Check if two string rotation of each othe** r
Write a program which accepts two given String and checks if they are the rotation of
each. If they then return true otherwise return false. A String is said to be a rotation of
other string if they contain same characters and the sequence is rotated across any
character, e.g. "dabc" is a rotation of "abcd" but "dbac" is not. If you want to practice
more string-based questions, you can also see my list of 20 String-based algorithm
questions from Java interviews.
**49. LRU cache in Java** (solution)
Write a program to implement an LRU cache in Java. An LRU cache means Least Recently
Used Cache which removes the least recently used element if the cache is full. You can


use LinkedHashMap to implement LRU cache in Java.

**50. Merge sort**
Implement the merge sort algorithm in Java. You can write a recursive or iterative
solution, whichever you like. You also need to explain the time and space complexity for
the best, worst, and average case.

Ref : https://javarevisited.blogspot.com/2017/07/top-50-java-programs-from-coding-Interviews.html
