### LIST
A list is a data structure that’s built into Python and holds a collection of items. Lists have a number of important characteristics:

  1. List items are enclosed in square brackets, like this [item1, item2, item3].
  2. Lists are ordered – i.e. the items in the list appear in a specific order. This enables us to use an index to access to any item.
  3. Lists are mutable, which means you can add or remove items after a list’s creation.
  4. List elements do not need to be unique. Item duplication is possible, as each element has its own distinct place and can be accessed separately through the index.
Elements can be of different data types: you can combine strings, integers, and objects in the same list.

### ARRAY
An array is also a data structure that stores a collection of items. Like lists, arrays are ordered, mutable, enclosed in square brackets, and able to store non-unique items.

But when it comes to the array’s ability to store different data types, the answer is not as straightforward. It depends on the kind of array used.

### LIST VS ARRAY
  1. Arrays need to be declared. Lists don’t,
  2. Arrays can store data very compactly
  3. Arrays are great for numerical operations;

  - If you need to store a relatively short sequence of items and you don’t plan to do any mathematical operations with it, a list is the preferred choice. This data structure will allow you to store an ordered, mutable, and indexed sequence of items without importing any additional modules or packages.
  - If you have a very long sequence of items, consider using an array. This structure offers more efficient data storage.
  - If you plan to do any numerical operations with your combination of items, use an array. Data analytics and data science rely heavily on (mostly NumPy) arrays.
