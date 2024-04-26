# CenterElementsWithCSS
Center elments horizontally, and vertically.

### To center text in the middle of a div: `<div>` <br>
`html` <br>
`<div class="container">`<br>
 `<h1>Hello world</h1>`<br>
`</div>` <br>
`css` <br>
 `h1 { text-align: center; }` <br>

![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/a2a492c3-df59-4211-abf8-afa02cf85bfb)
<br>

To center everything in the container add the css property to the container not just the h1 element:<br>
`html` <br>
`<div class="container">`<br>
 `<h1>Hello world</h1>`<br>
 `<p>I'd like to be centered too</p>`
 `<p>Same here!</p>`
`</div>` <br>
`css` <br>
 `.container { text-align: center; }` <br>

![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/36e46f00-b6d7-42c2-bfb5-bcd24eb98675)<br>
Here the property in the container is **inherited** from the container div down to the other element to center them. 

### Center an element or a box to the center of a container:<br>
Html<br>
 `<div class="container">`<br>
        `<div class="child"></div>`<br>
 `</div>`<br>
 CSS <br>
 `.container {`<br>
    `outline: dashed 4px black;`<br>
   ` width: 350px;`<br>
   ` height: 200px;`<br>
   ` text-align: center;`<br>
   ` margin-top: 50px;`<br>
   ` margin-left: 50px;`<br>
`} `<br>
`.child {`<br>
   ` width: 80px;`<br>
   ` height: 80px;`<br>
   ` background-color: red;`<br>
`}`<br>
![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/562e6c1f-43ff-45a0-a1b5-48b7d272f6ec)<br><br>
 ###### ADD TO CHILD CSS<br>
`.child {`<br>
   ` margin: 0 auto;`<br>
`}`<br>
Auto will allow the left and right margins take up all the remaining space available to them and put the box in the middle<br>

![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/0479d6b8-cff4-4c7b-936b-e640c26e082e)<br>
<br>
To move the box to the far right side of the container<br>
CHANGE THE CHILD MARGIN VALUES:<br>
`.child {`<br>
   ` margin-left: auto;`<br>
`}`<br>
Changing the margin left to auto allows the left side to take as much of the space available and pushed the box to far right.<br>
![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/d33a1fe6-8d35-4b98-b7ba-320f96996792)<br>
To move the box to the far left side of the container<br>
CHANGE THE CHILD MARGIN VALUES:<br>
`.child {`<br>
   ` margin-right: auto;`<br>
`}`<br>
Changing the margin right to auto allows the right side to take as much of the space available and pushed the box to far left.<br>
![image](https://github.com/nafizjiwa/CenterElementsWithCSS/assets/56348190/db675877-be3e-4ef2-9f1e-c68a0d119f8a)
***
 ###### TO CENTER IN FLEX BOX<br>

 










