# 1- What is a ‘Controlled Component’?
### An input form element whose value is controlled by React.
# 2- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
### It can sometimes be tedious to use controlled components, because you need to write an event handler for every way your data can change and pipe all of the input state through a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library. In these situations, you might want to check out uncontrolled components, an alternative technique for implementing input forms.
# 3- How do we target what the user is entering if we have an event handler on an input field?
```
let target =event.target;
```

/////////////////
# 1- Why would we use a ternary operator? 
### Shorten your if statements into one line of code with the conditional operator

# 2- :-
```
// if condition
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

//Ternary
x===y ?  console.log(true) :  console.log(false)

```