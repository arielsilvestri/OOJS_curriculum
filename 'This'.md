**Challenge Name: Introducing "This"**

**Challenge**

Make code more reusable with “this”.

**Challenge Description**

We are going to look at our `sayName method` from the previous example

```javascript
  sayName: function() {return "The name of this duck is " + duck.name + "."}
```

Notice how we are referencing our object's `name`, duck, when accessing its name `property`. While this is a totally valid way to access our object's `property`, there is a bit of a pitfall here.

What if the name of our `object` changes? What if, instead of a duck, it's a mallard now? Well, we would have to change `duck.name` to `mallard.name`. In this small example, that's fine, but what happens when we have an `object` that makes many references to its `properties` throughout its `methods`? Now the process gets much more complex!

There's a way to avoid that all. Introducing...`this`:

```javascript
var duck = {
  name: "Aflac",
  numLegs: 2,
  sayName: function() {return "The name of this duck is " + this.name + "."}
} 
```

`This` is a very robust topic that would be a great idea to research more deeply. For now, understand that `this`, in the current context, refers to the `object` that our `method` is associated with-duck. 

Now, if we changed our object's name to mallard, we don't have to find all our references to duck in our code. We've made our code highly reusable and easy to read.

**Instructions**

Refactor the code below so that the Dog `object` follows the same code style as the Duck `object`.

**Challenge Seed**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4,
  sayLegs: function() {return "This dog has " + dog.numLegs + " legs."}
}

dog.sayLegs();
```

**Challenge Tests**

Test to see if `dog.sayLegs()` still returns the desired string.
assert(dog.sayLegs() === “This dog has 4 legs.”), ‘message: `dog.sayLegs()` should return the desired string.’

**Challenge Solution**

```javascript
var dog = {
  name: “Spot”,
  numLegs: 4,
  sayLegs: function() {return "This dog has " + this.numLegs + " legs."}
}

dog.sayLegs();
```
