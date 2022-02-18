# Class 09: - Forms and JS Events

- ## Chapter 7: “Forms” (p.144-175)
- ## Chapter 14: “Lists, Tables & Forms” (pp.330-357)
- ## Chapter 6: “Events” (pp.243-292)
<hr>

## Forms
- `forms`: creates a tag that allows you to add form controls get all sorts of functionality on your webpage. Mainly to enable user input. 
- `form control`: creates the type of user input that will be used inside the form tag. 
- `input`: this tag is what will be holding your form controls. 
- `drop down list`
```
<form action="http://www.example.com/profile.php">
<p>What device do you listen to music on?</p>
<select name="devices">
 <option value="ipod">iPod</option>
 <option value="radio">Radio</option>
 <option value="computer">Computer</option>
 </select>
</form>

```
form input information is sent in name/value pairs
<hr>

# Chapter 14: “Lists, Tables & Forms” (pp.330-357)

- `show`: shows the borders of any empty cells
- `hide`: hides the border of any empty cells.
- `inherit`: when tables are nested inherit is used to make sure the inner table has the same properties as the outer table.
- `list-style-type`: allows you to control the shape or style of a marker(bullet).

### Key takeaway
- ### Table cells can have very wonky borders and spacing at first but you can use<br> properties to make style them, and make them more consistent.

- ### ist markers or bullets can be changed using list-style-type properties. 

<hr>

## Chapter 6: “Events” (pp.243-292)

- `events`: Something that occurs when the user or the browser manipulates the page. These events can be used to trigger code. Through DOM 

### How events trigger code
```
1. selects the element node
the script will respond to.


2.Indicate which event on
the selected node(s) will
trigger the response. 

3.State the code you want
to run when the event
occurs. 


jquery(pg.255)
```
<!-- <br> -->

- `event listener`: can be used to deal with more than one function at a time when handling events.

- `event bubbling`: default flow of events. they start a specific node then it flows outward to the least specific ones.

- `event capturing`: changes the flow of events to inward which is the opposite of `event bubbling`.

`Event listeners is attached to the window object (not the document object).`

- `mutation events `: happens when part of the page is changed or altered.

Note: I feel like these events are what were doing in class with the prompts but to understand the most basics of them we didn't jump right into events. In the future when making webpages we would just make those events for the questions. 



