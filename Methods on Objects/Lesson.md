<h1>JavaScript Object Methods</h1>
<h2>Challenge</h2>
<p>Add a method to an object in JavaScript.</p>

<h2>Challenge description</h2>
<p>Now that we know how to create an object and access its properties, let's explore a special property of objects. Namely, we will talk about adding a method to our existing objects!</p>
<p>Methods are properties that are functions. You can do all sorts of things with these methods. Let's look at our previous duck example, and add a method:</p>

```javascript
var duck = {
  color: "white",
  legs: 2,
  swim: true,
  sayColor: function() {return "This duck's color is " + duck.color + "."}
} 

duck.sayColor();
//This will return "This duck's color is white."
```

<p>As you can see above, we added the sayColor method, which is a function that we can call to return a sentence telling us the color of the duck. This is a straightforward method of adding a method to an object in JavaScript.</p>
<p>Notice that we access the color of the duck in the method. We'll get back to that in the next lesson, but for now, this is the way we will insert that value into the string.</p>
<p>In the following exercise, I would like for you to draw upon the previous Vulture object you created, and give a function sayLegs. This function should return a sentence that says "This vulture has 2 legs."</p>

<h2>Challenge Seed</h2>
```javascript
var vulture = {
  color: "black".
  legs: 2,
  swim: false,
  //Add your method here.
}

vulture.sayLegs();
```

<h2>Challenge Tests</h2>
<ul>
  <li>Test to see if the vulture object has a sayLegs method that returns the desired string.</li>
</ul>

<h2>Challenge Solution</h2>
```javascript
var vulture = {
  color: "black".
  legs: 2,
  swim: false,
  sayLegs: function(){return "This vulture has" + vulture.legs + "legs."}
}

vulture.sayLegs();
```