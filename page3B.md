---
layout: default
title: Page3B
parent: Dropdown
---

<h1>This is Page 3B</h1>


<h2>My First JavaScript</h2>

<button type="button" id="demo"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<!-- p id="demo"></p> -->

<p>Replace "Microsoft" with "W3Schools" in the paragraph below:</p>

<button onclick="myFunction()">Try it</button>

<p id="demo2">Please visit Microsoft!</p>
<button id="Button2"  onclick = "changeBgColor(this)">Change background color</button>

<script>
function myFunction() {
    var str = document.getElementById("demo2").innerHTML;
    var txt = str.replace("Microsoft","W3Schools");
    document.getElementById("demo2").innerHTML = txt;
}

function changeBgColor(id) {
id.style.backgroundColor = "Lightblue";
}
</script>

<!-- document.getElementById("demo").innerHTML = -->
