**Challenge Name: JavaScript Object Methods**

**Challenge**

Create a method on an object.

**Challenge description**

Now that we know how to create an `object` and access its `properties`, let's explore a special property of `objects`. Namely, we will talk about adding a `method` to our existing `objects`!

`Methods` are `properties` that are `functions`. We can do all sorts of things with these `methods`. Let's look at the previous Duck example, and add a `method`:

```javascript
var duck = {
  name: "Aflac",
  numLegs: 2
  sayName: function() {return "The name of this duck is " + duck.name + "."}
} 

duck.sayName();
//This will return "The name of this duck is Aflac."
```

As you can see above, we added the `sayName method`, which is a `function` that we can call to return a sentence telling us the color of the duck. This is a straightforward method of adding a `method` to an `object` in JavaScript.

Notice that we access the `name` of the Duck in the `method`. We'll get back to that in the next lesson, but for now, this is the way we will insert that value into the string.

**Instructions**

In the following exercise, draw upon the previous Dog `object` you created, and give it a `method sayLegs`. This `method` should return a sentence that says "This dog has 4 legs."

**Challenge Seed**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4
  //Add your method here.
}

dog.sayLegs();
```

**Challenge Tests**

Test to see if the Dog `object` has a `sayLegs method` that returns the desired `string`.
assert(typeof(dog.sayLegs() === ‘function’), ‘message: `dog.sayLegs()` should be a function.’
assert(dog.sayLegs() === “This dog has 4 legs.”), ‘message: `dog.sayLegs()` should return the desired string.’

**Challenge Solution**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4
  sayLegs: function() {return "This dog has " + dog.legs + " legs."}
}

dog.sayLegs();
```
