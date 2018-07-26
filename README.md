<!-- Put the name of the project after the # -->
<!-- the # means h1  -->
# Basic-Portfolio

<!-- Put a description of what the project is -->
Learn html, css, floats, box model, position

# Link to deployed site
<!-- make a link to the deployed site --> 
<!-- [What the user will see](the link to the deployed site) -->
[Basic-Portfolio](https://fruit13ok.github.io/Basic-Portfolio/)

# Images
<!-- take a picture of the image and add it into the readme  -->
<!-- ![image title](path or link to image) -->
<!-- ![wireframe](https://pngimg.com/uploads/minions/minions_PNG78.png) -->
![Basic-Portfolio](images/md_image1.png)
![Basic-Portfolio](images/md_image2.png)
![Basic-Portfolio](images/md_image3.png)

# technology used
<!-- make a list of technology used -->
<!-- what you used for this web app, like html css -->

<!-- 
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item. 
-->
- HTML
- CSS

# code snippets
<!-- put snippets of code inside ``` ``` so it will look like code -->
<!-- if you want to put blockquotes use a > -->

```
<div class="myPortfolioDiv clearfix">
    <div class="float-left myrelative">
        <img src="assets/images/minions_PNG72.png">
        <p class="myabsolute mycaption">caption 1</p>
    </div>
    <div class="float-left myrelative">
        <img src="assets/images/minions_PNG73.png">
        <p class="myabsolute mycaption">caption 2</p>
    </div>
    <div class="float-left myrelative">
        <img src="assets/images/minions_PNG74.png">
        <p class="myabsolute mycaption">caption 3</p>
    </div>
    <div class="float-left myrelative">
        <img src="assets/images/minions_PNG75.png">
        <p class="myabsolute mycaption">caption 4</p>
    </div>
    <div class="float-left myrelative">
        <img src="assets/images/minions_PNG76.png">
        <p class="myabsolute mycaption">caption 5</p>
    </div>
</div>
```
```
.myPortfolioDiv {
    position: relative;
    width: 66%;
    height: 100%;
    border: 3px solid #73AD21;

}
.clearfix::after {
    content: "";
    display: block;
    clear: both;
}
.float-left {
    float: left;

}
.float-right {
    float: right;
}
img {
    width: 180px;
    height: 180px;
}
.myrelative {
    position: relative;
}
.myabsolute {
    position: absolute;
    bottom: 10%;
    left: 0%;
}
.mycaption {
    width: 100%;
    text-align: center;
    background-color: #4aaaa5;
    color: #ffffff;
}
```
> This is how to use float and position together


# Learning points
<!-- Learning points where you would write what you thought was helpful -->
To style HTML, mainly about **_float and position_**

# Author 
<!-- make a link to the deployed site and have your name as the link -->
Yi Liu

# License
Standard MIT License