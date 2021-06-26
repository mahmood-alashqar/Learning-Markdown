# Domain Modeling

### Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

### A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

# Define a constructor and initialize properties 


### Here's an implementation of the EpicFailVideo constructor function.
  ```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);

  ```

  > This is object-oriented programming in JavaScript at its most fundamentalb level.

* The new keyword instantiates (i.e. creates) an object.
* The constructor function initializes properties inside that object using the this variable.
* The object is stored in a variable for later use.

## Here's some tips to follow when building your own domain models.

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.

# There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.

> When representing information in a table, you need to think
in terms of a grid made up of rows and columns (a bit like a
spreadsheet). you just need to learn how to:
* Use the four key elements for creating tables
* Represent complex data using tables
* Add captions to tables