# _Epicodus Codealong_

## C# Arrays Notes

#### _Array vs. List_
JavaScript arrays are flexible. They can contain a variety of different things and their size automatically fluctuates when items are added or removed.

On the other hand, C# includes both arrays and lists. They're each collections of multiple items, but are very different:

A list is similar to arrays in JavaScript. However, they generally only hold one type of data (like string or int). They fluctuate in size as items are added or removed.

An array is stricter and has a set length. After an array is created, we cannot add or remove objects to make it larger or smaller. All items stored in an array must be the same data type (such as string or int).

#### _Arrays_
We can create an array containing strings in our REPL like this:
```sh
> string[] fruits = { "apples", "bananas", "oranges", "grapes" };
```

We can create an array of integers like this:
```sh
> int[] primeNumbers = { 2, 3, 5, 7, 11 };
```

There are several steps to creating a C# array:

1. Determine what type of data the array contains. Data in C# arrays must be the same type. To define an array, we must first determine what data type it will hold. In the examples above, we state string when creating an array of fruits and int when creating an array of numbers.

2. Append square brackets [] to the data type. These allow us to declare that the object we're about to create will be an array. In the example above, int[] means an array of integers. string[] represents an array of strings. There should be no spaces between the data type and square brackets.

3. Include a variable name. After declaring the array and type of data it holds, include a name. In the examples above, we used string[] fruits and int[] primeNumbers.

4. Assign data to the array. We use the assignment operator = to assign the array variable a list of information. Note this is inside {}, or curly brackets, not the square brackets we used for JavaScript arrays. Remember that the length of the array may not change after you assign it.

#### _Accessing Array Data_

* We can access an array by calling the array's variable name.
* To access a specific entry in the array, we append square brackets [] to the array's variable name. Inside the brackets we provide the index of the item we want.

#### _Altering Array Data_
* We cannot change an array's length but we can change values inside it. 
* We already know we can call fruits[2] to access the second index of our fruits array. This time we just include the = operator to assign a new value.This can be done for any index of the array.