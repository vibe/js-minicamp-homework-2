#### For

* A `for` loop is wrapping code that is used to repeat a certain section of code a certain number of times based
on an expression, each for loop consists of a statement that runs at the intial start of the for loop intialization,
a conditional expression that determines if the loop will continue to run, followed by another statement that will
execute at the end of each loop iteration.

```javascript
    for (<statement>; <expression>; <statement>){
        <code>
    }
```
Think about having a sink of dirty dishes, you essientially repeat the same action over and over until all the cleans are done.
You initize the action by having 0 clean dishes and you will only be done when you the clean dishes is as many as the number of dirty dishes you started with, at the end of cleaning a dish you add one to the cleaned dishes. 

```javascript
    var dirtyDishes = 9;

    for(var platesWashed = 0; platesWashed < dirtyDishes; platesWashed++) {
        washPlate();
    }
```


#### &&, ||, !

 * &&  - The && symbols stand for an `and` operation, when using this operator it is saying both sides of operator must evalulate
 to a truthy value in order for the condition to be true. For example, to be dressed, you must be wearing a shirt `and` pants othewrise you are not dressed.

```javascript
 var hasShirt = true;
 var hasPants = true;
 var isDressed = false;

 if(hasShirt && hasPants) {
     isDressed = true;
 }

```

* || - the `||` symbols stand for an `or` operation, when using this operator it is saying either side of the operator must evaluate to a truthy value in order for the condition to be true. For example, in order to make a sandwhich you need peanut butter or ham.

```javascript
var hasPeanutButter = true;
var hasHam = true;

if (hasPeanutButter || hasHam) {
    makeSandwhich();
}
```

* ! - The `!` operator is used to represent a `not` operation. It is used to tranform a boolean value.

 `!true === false`
 `!false === true`

 #### Arrays
 * Arrays are a collection or sequence of variables. Arrays are used to store data usually of similar data types and used to organized your data in a sequence that can be looped over and transformed. Think about having a collection of markers instead of having markers all over the place, you can create an array and each array slot would be one of the markers. 

```javascript
 var one = 1;
 var two = 2;
 var three = 3;

 var arrayOfNumbers = [1, 2, 3]

 ```

 #### Git
 * git is version control system. Git is used to track every change to your code as you add and remove to it.  Git allows you to work and collab with multiple people on a project at once, tracking everyone's changes.

 #### Github 

 * Github is a website which uses `git` to power a community of open source projects. Here you collab with other developers on projects and push changes to repositories that hold code. You can also create your own repos for other developers to help build on your projects.

 