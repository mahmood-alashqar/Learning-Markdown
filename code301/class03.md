# 1- What does .map() return?
### anything!
# 2-If I want to loop through an array and display each value in JSX, how do I do that in React?
```
function NumberList(props) {
  const numbers = props.numbers;
  return (
    <ul>
      {numbers.map((number) =>
        <ListItem key={number.toString()}
                  value={number} />
      )}
    </ul>
  );
}
```
# 3- Each list item needs a unique IDs for Keys.
# 4- What is the purpose of a key?
### help React identify which items have changed, are added, or are removed.
/////////////////////////
# 1- What is the spread operator?
### In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
# 2- List 4 things that the spread operator can do.
* to the rescue
* find a specific result in an array that use Math laibrary
* “spreads” the array into separate arguments.
* Copying an array
* Concatenating or combining arrays
# 3- Give an example of using the spread operator to combine two arrays.
```
const hello = [...["12345"]] ;
const world = [..."123456789"];

const helloWorld = {...hello,...world}
```
# 4- Give an example of using the spread operator to add a new item to an array.
```

const fewFruit = ['🍏','🍊','🍌'];
const fewMoreFruit = ['🍉', '🍍', ...fewFruit];
```
# 5- Give an example of using the spread operator to combine two objects into one.
```
const objectOne = {hello: "hi"};
const objectTwo = {world: "uneversal"};
const objectThree = {...objectOne, ...objectTwo};
```
///////////////////////////////////////////
# 1- In the video, what is the first step that the developer does to pass functions between components?
### Create the function where is the state that i want to change is
# 2- In your own words, what does the increment function do?
### it increase a specific counters when condition of the matching is true
# 3- How can you pass a method from a parent component into a child component?
```
// in parent class
newFunctionNameAsVariable = this.nameOfTheFunction;
// in childrenClass = this.props.newFunctionNameAsVariable;
```
