# minihack_app

## Member

1. Jirayu Laungwilawan    5910546635
2. Archawin Tirugsapun    5910545892
3. Sirasath Piyapootinun  5910546465
4. Tharit Pongsaneh       5910546406

## Activity1

### Q.1
```html
html
head
meta
meta
meta
title
"Standford"
<link>
body
<div id = "header">
<a>
<img>
<a>
<img>
<h1>
C5231n...
<div class = "text-center">
<h4>
Spring...
<div id = "teaser">
<div id = "convnetvis">
<div class = "layer">
.....
<div class = "container">
<div>
<div class = "sechighlight">
<div>
<h2>
<div>
"....."
<div class = "container sec">
<div>
<div>
.....
<div>
.....
<div class = "sechighlight">
<div>
<a>
......
<div class = "container sec">
<div>
<div>
.....
.....
<div class = "container sec">
<div>
<div>
....
.....
<div class = "sechighlight">
<div>
<h2>
......
<ul>
......
<div class = "container sec">
<h2>
<div>
......
......
<div class = "sechighlight">
<div>
<div>
<a>
<button>
<div>
<a>
<img>
<script>
<script>
```
### Q.2

Each box has a dimension of `120px * 120px` and has a border `0px` but has a `10px` `margin` at the bottom of each images. The font size of each name is `16px`. All of these boxes has an `event listener`. Its box sizing is a border box so border is created automatically for all the boxes. But for the whole section of "Instructors Teaching Assistants" there is a `margin` on both the left and right side of `15px` each. The Instructors and the Teaching Assistants both have a `padding` on the left and right of `15px`.

### Q.3

In the `div` of the Instructors sections, after the closing of the first Serena Yeung `div`, add a `<br>`
to leave a line and add your image by using
```html
<img src="https://pbs.twimg.com/profile_images/378800000822867536/3f5a00acf72df93528b6bb7cd0a4fd0c.jpeg">
```

### Q.4

The `div` `id` "convnetvis" is changing all the time. You can identify by looking at the `div`, everytime the information is changed, the word `div` is always highlighted in pink.

### Q.5

They get all picture from `https://www.cs.toronto.edu/~kriz/cifar.html` or `CIFAR-10`. I look up in the `source page` -> `cs231n.stanford.edu` -> `convnet_demo` -> `convnet_demo.js` in the commend line they told that they dowload image from `CIFAR-10`.

### Q.6

In the html file I find the element of that bar graph and it show that it use div class pp to represent it so I look in the source page -> cs231n.stanford.edu -> style.css and I find the pp class in that class it has a background-color for bar graph so I change it to rgb(0,0,255) to make it blue.

## Activity2

### Q.1

Remove `myGameArea.start();` in `startGame()` and wait until restart button got press then set `myGameArea.start();`

### Q.2

In the file `game.html` first in the function `updateGameArea()` in the line 129 and 130 change the third parameter to yellow.

```javascript
myObstacles.push(new component(10, height, "yellow", x, 0));
  myObstacles.push(new component(10, x - height - gap, "yellow", x, height + gap));
```

Second, in the function `startGame()` when we create the `myGamePiece` in line 39 change the third parameter to blue.

```javascript
myGamePiece = new component(30, 30, "blue", 10, 75);
```

### Q.3
Create the button pause that will `PAUSE` when you click it the pause in `myGameArea` will swap to opposite value.
```html
 <button id = "pause" onclick = "myGameArea.pause = !myGameArea.pause">PAUSE</button>
 ```

### Q.4
Create a new attribute (life) and and in `updateGameArea` that if `myGamePiece` crash with `obstacle` then + the attribute by `1` and if `life` is >= 3 then stop else remove the `obstacle`.
