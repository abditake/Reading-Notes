# [Class 03: HTML Text, CSS Introduction, and Basic JavaScript Instructions](/README.md)

- ## [Chapter 3: “Lists” (pp.62-73)](#html1)
- ## [Chapter 13: “Boxes” (pp.300-329)](#html2)
- ## [Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)](#html3)
- ## [Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)](#html4)

# <a name="html1">Chapter 3: “Lists” (pp.62-73</a>
### `ol`: Creates an ordered list
### `ul`: Creates an unordered list
### `d1`: Creates a definitions list 
### `li`: Opening and closing tags for any items within a list.
### `dt`: acts like the li of the `d1` element. Opening and closing tags are used within the `d1` tag.
### `dd`: The tag that actually contains the definition.
### `Nested lists`: indented sub-list within a list.
## There are three types of lists, ordered, unordered and nested. Ordered lists use numbers, unordered lists use bullets, and nested lists are just lists inside a list. 
<hr>

# <a name="html2">Chapter 13: “Boxes” (pp.300-329)</a>
### `border`: Separates the edge of one box from another.
### `margin`: Sits outside the border. Space between two boxes.
### `Padding`: Space between the border and the content. 
### `border color`: This colors the border around a box.
### `display`: allows to change a inline element into a block level element.
### `inline`: makes a block level element into an inline.
### `block` : Turns a inline element into a block level element.
### `none`: used to hide elements from the page.
### `visibility`: Has two values; hidden and visible. this either shows or hides an element.
### `border-images`: Creates an image to the border of a box.
### `border-radius`: Creates rounded corners on a box.
<br>

# <a name ="html3">Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)</a>
### There will be times where using quotes inside strings are needed for contractions. You can achieve this by using a double quote then a single quote for your word.
  - Storing booleans into a variable to use for if statements to respond to input.  
### Javascript overwrites variables by which ever gets defined last. The code won't throw up errors if there are your variables being defined, it will just go with the last one. 
<br>

# <a name="html4">Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)</a>
### Loops Check a condition and if it returns true will run a code block. For loops will continue until the returned value is false. There are three main loops.
- For Loop
- While loop
- Do While loop
<br>

``` 
    condition(counter)---> how many times the code will run
keyword                ^               
  _|_       ___________|____________     
 |   |     |                        |    
  for       (var i = 0; i < 10; i++>)     {
            document.write(i)             |
  }        |_________________|            V 
  |                 |                   opening
  |                 |
  v                 v
closing       code to execute

```

### For loops use  a counter as a condition. This allows them to know how many times to run the loop. The counter is broken up in three parts.
  - initialization `---> var i - 0`
  - condition `---> i<10`
  - update `---> i++`
```
  var i;
  for (i=0; i<10 ; i++){

  }

```
### `break`: used to terminate a loop.
### `continue`: tells the interpreter to continue with the loop.
### `arrays(loops)`: can be used to determine how many times to run the code depending on what is stored in the array.
### `infinite loop`: when a condition never returns false.

