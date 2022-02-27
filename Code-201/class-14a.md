# [Class: 14a - CSS Transforms, Transitions, and Animations](/README.md)

- ## CSS Transforms, Transitions, and Animations

<hr>

Best CSS effects in the readings


 ## `swing`: this just moves the container left and right. I would use this for a wrong guess on an answer.
```
.swing:hover
{
        -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;
}

```

## `grow`: just enlarges the texts are you hover it.
```
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
```

## `transform`: this just changes or distorts the element how you want. 

 - ## syntax
 ```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

 ``` 

Transformation allows for cool and creative ways to style your webpage even more creating that wow factor that would otherwise leave your page tasteless. you can also add animation ontop of that to create transitions that change the webpage entierly which is cool. 