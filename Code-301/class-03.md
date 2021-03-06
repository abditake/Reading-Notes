# [Class 03: React and Forms](/README.md)

- ## React Docs - lists and keys
- ## The Spread Operator
<hr>


# What does .map() return?
      - map returns a new array.

- ## If I want to loop through an array and display each value in JSX, how do I do that in React?
      - Using curly braces.
```
You can build collections of elements and include them in JSX using curly braces {}.

```


- ## Each list item needs a unique ____.

      - key

- ## What is the purpose of a key?
      - to specifically identify which items have changed or added or removed.
    

<hr>

# The Spread Operator

- ## What is the spread operator?
    - spreads array's into seperate arugments


- ## List 4 things that the spread operator can do.
      - copy an array
      - add to state in react
      - converting nodelist to an array
      - combining objects

- ## Give an example of using the spread operator to combine two arrays.
  ```
  const myArray = [`ðĪŠ`,`ðŧ`,`ð`]
  const yourArray = [`ð`,`ðĪ`,`ðĪĐ`]
  const ourArray = [...myArray,...yourArray]
  console.log(...ourArray) // ðĪŠ ðŧ ð ð ðĪ ðĪĐ

  ```
- ## Give an example of using the spread operator to add a new item to an array.
```
const fewFruit = ['ð','ð','ð']
const fewMoreFruit = ['ð', 'ð', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]

```
- ## Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "ðĪŠ"}
const objectTwo = {world: "ðŧ"}
const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
objectFour.laugh() // ððððð

```