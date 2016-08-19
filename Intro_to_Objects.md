**Challenge Name: Introduction to Objects**

**Challenge**

Create a basic JavaScript object.

**Challenge Description**

Think about things we encounter in our everyday life, like cars, shops, and birds. These are all objects: tangible things we can observe and interact with.

What are some qualities of these `objects`? A car has wheels. Shops sell items. Birds have wings. 
These qualities, or `properties`, define what makes up an `object`. It's important to note that cars might all have wheels, but not all cars will have the same number of wheels.

We can use `objects` in JavaScript to model real-world objects, endowing them with properties and behavior just like their real-world counterparts. We’ll use the previous concepts to create a Duck `object`:

```javascript
var duck = {
  name: "Aflac",
  numLegs: 2
} 
```
We created a Duck object with two property/value pairs: a `name` of Aflac and a `numLegs` of 2. 

**Instructions**

Create a Dog `object` with `name` and `numLegs properties,` and set them to a string and a number, respectively.

**Challenge Seed**

```javascript
var dog = {
  //Your code here
}
```
**Challenge Tests**

Test to verify that the dog object is defined.
assert(typeof(dog) === “object”), ‘message: `Dog` should be an object.’;

Test to verify that the dog object has name and numLegs properties.
assert(typeof(dog.name) === ‘string’), ‘message: `dog.name` should be a string;
assert(typeof(dog.numLegs) === ‘number’), ‘message: `dog.numLegs` should be a number;

**Challenge Solution**

```javascript
var dog = {
  name: //string,
  numLegs: //number
}
```