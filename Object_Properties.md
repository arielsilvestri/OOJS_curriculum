**Challenge Name: Accessing Properties on Objects**

**Challenge**

Use dot notation to access object’s properties.

**Challenge Description**

Great job on defining that Dog `object`. Now that we have created an `object`, let's talk about accessing some of these properties!

It's very simple to access the values of a property on an `object`. See the following example:

```javascript
var duck = {
  name: "Aflac",
  numLegs: 2
} 

console.log(duck.name)
//This will print "Aflac" to the console. 
```

By using our `object` name, `duck`, along with the property whose value we want to utilize, `color`, we access the `property` of your `object`.

**Instructions** 

Print the properties of the Dog object below to your console.

**Challenge Seed**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4
}

//Add your two console calls here.
```

**Challenge Tests**

Test to see that the Dog’s name prints to the console.
assert(console.log(dog.name) === “Spot”), ‘message: `console.log(dog.name)` should print out “Spot” ‘
 
Test to see that the Dog’s numLegs prints to the console.
assert(console.log(dog.numLegs) === 4), ‘message: `console.log(dog.numLegs)` should print out the number 4.’

**Challenge Solution**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4
}

console.log(dog.name);
console.log(dog.numLegs);
```
