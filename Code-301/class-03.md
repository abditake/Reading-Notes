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
  const myArray = [`🤪`,`🐻`,`🎌`]
  const yourArray = [`🙂`,`🤗`,`🤩`]
  const ourArray = [...myArray,...yourArray]
  console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

  ```
- ## Give an example of using the spread operator to add a new item to an array.
```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

```
- ## Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

```