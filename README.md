# Javascript Arrays
Arrays in Data Structures and Algorithms with JavaScript - There are lot of resources out there that covers Arrays in JavaScript but only few explain the topic for the purpose of Data Structures and Algorithms. In this explanation, I will scratch the surface of the topic to give you a beginners guide to understanding Arrays in Data Structures and Algorithms with JavaScript. Maybe, this will prompt a short book on Data Structures and Algorithms with Javascript. 
You are free to ask question and as well contribute to make it better. 
# Introduction to Arrays in JavaScript
Arrays is one of the most powerful and widely use data structure concept in any programming language. It can as well be called Arrays Data Structure. 

**Arrays are use to store or holds a fixed number of values of a single type**. 

For any Array created, you can perform **four operations on it which are Access, Insertion, Deletion, and Search**. 

Another interesting thing about Arrays - It has length (fixed when it is created) and index. Let's look at image below and example 1.0 to understand what I meant by length and index. 

![Array Sample Image](https://docs.oracle.com/javase/tutorial/figures/java/objects-tenElementArray.gif "Array sample image")

##### Figure 1.0: An array of 10 elements. Image credit: [Oracle](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html) 

##### Example 1.0:

`var myArray = [3, 8, 4, 9, 7, 6];`

If you count the elements inside myArray, it has 6 elements. Which means, it has a length of 6 and index of 5 (note: counting index always start from 0).


# Access 

You can access an Array or element(s) in array by specifying the index number of the array you want to access such as *`arrayName[index]`*. Let's take a look at Example 1.1 below

##### Example 1.1:

```
var myArray = [3, 8, 4, 9, 7, 6];

myArray[2]; //will returns 4.

myArray[4]; //will returns 7

```

Accessing array is that simple. 😄

##### P.S: For the purpose of data structure and algorithms.
I need to mention that the time complexity of accessing an array at a specified index only takes constant time O(1). Simply put, the access method uses the index to get the value directly from the address in memory. Don't worry about how we got this, I will cover Big O Notation (Time Complexity and Space) in another topic soon and put a link here.


