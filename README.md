# Python Lists, Loops And List Comprehension

## Objectives

- Learn how to build and manipulate python lists
- Learn how to loop through lists
- Learn List Comprehension

## What Are Lists?

Lists are just a fancy term for `array`, most programming languages use the term `list` to describe a data structure that can hold multiple values that can all have different data types. List's are iterable and can be modified.

Here's an example of a list/array:

```js
let myArr = [1, 2, 3, 4]
let otherArr = new Array()
```

```python
my_list = [1,2,3,4]
other_list = list()
```

We can declare lists either by using `[ ]` brackets or with the `list` constructor/method.

## You Do

In `main.py` perform the following:

- Create a `list` and store it in a `nums` variable that contains all numbers from 1-5.
- Create a `list` and store it in a `chars` variable that contains all letters a-e.

## Manipulating Lists

We can also manipulate lists in python such as adding items or joining lists. Let's see some examples:

- If we wanted to join lists:

  - In Javascript we can use the spread operator to join arrays:

    - > ```js
      > let numArr1 = [1, 2, 3]
      > let numArr2 = [4, 5, 6]
      > let allNums = [...numArr1, ...numArr2]
      > ```

  - Or the concat method:
    - > ```js
      > let numArr1 = [1, 2, 3]
      > let numArr2 = [4, 5, 6]
      > let allNums = numArr1.concat(numArr2)
      > ```
  - In python we can use the `+` operator:
    - > ```python
      > num_list1 = [1,2,3,]
      > num_list2 = [4,5,6]
      > all_nums = num_list1 + num_list2
      > ```

- What if wanted to add to the end of a list ?

  - Javascript has a `push` method:

    - > ```js
      > let arr = [1, 2, 3]
      > arr.push(4)
      > ```

  - Python has an `append` method:
    - > ```py
      > my_list = [1,2,3]
      > my_list.append(4)
      > ```
