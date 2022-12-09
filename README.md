# Bubble Sort Function

This is a simple implementation of the bubble sort algorithm using an asynchronous function. It is intended to be used to sort an array of numbers in ascending or descending order.

## Usage

The Bubble Sort Function takes two parameters: an array of numbers to be sorted, and a boolean value indicating whether the numbers should be sorted in ascending (true) or descending (false) order.

Example:

```javascript
let arr = [4, 3, 2, 1];
let sortAscending = true;

bubbleSort(arr, sortAscending);
```

Calling the function will return a sorted array in the order specified by the second parameter.

## Asynchronous Function

The Bubble Sort Function is implemented as an asynchronous function, meaning it will return a promise that will be fulfilled when the sorting is complete.
