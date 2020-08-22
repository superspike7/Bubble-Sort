# **The Odin Project - Ruby Programming**

### **Project: Bubble Sort**

### **Introduction:**
Sorting algorithms are some of the earliest that you typically get exposed to in Computer Science. It may not be immediately obvious how important they are, but it shouldn’t be hard to think of some examples where your computer needs to sort some massive datasets during everyday operations.

One of the simpler (but more processor-intensive) ways of sorting a group of items in an array is bubble sort, where each element is compared to the one next to it and they are swapped if the one on the left is larger than the one on the right. This continues until the array is eventually sorted.

This project is part of The Odin Project’s Ruby Programming [curriculum](https://www.theodinproject.com/courses/ruby-programming/lessons/bubble-sort).

### **Problem:**
Sort an array of numbers by checking each number and number next to it. If the first number is bigger than the next number then it should be swapped and then move to the next, other wise if the first number is smaller no swapping will be occured and proceed to the next.

### **Solution/Pseudocode:**
* get an array input from the user
* check if the array is already sorted and return if it is, if not do the bubble sort alg
* loop arr.length times
* inside the loop will be an itteration that swaps two elements of the array if the first one is bigger, else move the the next element and compare it to the element next to it.
* if the element next to it is nil, then end the itteration.
 return the array
