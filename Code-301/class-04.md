# [Class 04: React and Forms](/README.md)

- ## React Docs - Forms
- ## The Conditional (Ternary) Operator Explained
<hr>

# React Docs - Forms

- ## What is a ‘Controlled Component’?
    - A controlled element is a component that renders form elements and controls them by keeping the form data in the component's state.

- ## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
    - the code updates the state as the hits the enter button.

- ## How do we target what the user is entering if we have an event handler on an input field?
    - the handleChange setState's the value as the user hits submit, whatever they typed updates the state and that new input becomes the value and that value is shown on an alert using the handleSubmit. if you wanted to target the input you would use the this.state.value


```
  handleChange(event) {
    this.setState({value: event.target.value});
  }

  <input type="text" value={this.state.value} onChange={this.handleChange} />
```

<hr>

# The Conditional (Ternary) Operator Explained

- ## Why would we use a ternary operator?
      - it's just a shorter way to right an if statement. 

```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}

```

```
x===y? console.log(true): console.log(false)

```

    