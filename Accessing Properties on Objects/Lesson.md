<h1>Accessing Properties on Objects</h1>
<h2>Challenge</h2>
<p>Access each of the properties on our Vulture object</p>

<h2>Challenge Description</h2>
<p>Great job on defining that Vulture object! Now that you've created an object...let's talk about accessing some of those properties!</p>
<p>It's very simple to access the values of a property on an object. See the following example:</p>

```javascript
var duck = {
  color: "white",
  legs: 2,
  swim: true
}

console.log(duck.color)
//This will print "white" to the console. 
```

<p>By using your object name, duck, along with the property whose value you want to utilize, color, you access the property of your object. For now, that's all there is to it.</p>
<p>Go ahead and print the properties of the Vulture object below to your console.</p>

<h2>Challenge Seed</h2>
```javascript
var vulture = {
  color: "black".
  legs: 2,
  swim: false,
}

//Add your three console calls here.
```

<h2>Challenge Tests</h2>
<ul>
  <li>Test to see that the vulture's color is printed to the console.</li>
  <li>Test to see that the vulture's legs are printed to the console.</li>
  <li>Test to see that the vulture's ability to swim is printed to the console.</li>
</ul>

<h2>Challenge Solution</h2>
```javascript
var vulture = {
  color: "black".
  legs: 2,
  swim: false,
}

console.log(vulture.color);
console.log(vulture.legs);
console.log(vulture.swim);
```
