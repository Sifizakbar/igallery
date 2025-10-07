# Ex.08 Design of Interactive Image Gallery
## Date:07.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

gallery.html

<html>
    <head>
        <title>image gallery</title>
        <link rel="stylesheet" href="style.css">
        <script src="script.js"></script>
    </head>
<body>
        <div class="imgcont">
        <img src="sifiz1.jpg" id="t1" onclick="func1()">
        <img src="sifiz2.jpg" id="t2" onclick="func2()">
        <img src="sifiz3.jpg" id="t3" onclick="func3()">
        <img src="sifiz4.jpg" id="t4" onclick="func4()">
        </div>
        <div class="footer">SIFIZ A(25010152)</div>
</body>
</html>

style.css

body{
            display: flex;
            flex-wrap: wrap; 
            justify-content: center; 
            align-content: center;
            background-color: skyblue; 
            border: 3px solid black; 

}
.imgcont{
    width: 615px;
    padding: 15px; 
    margin: 100px; 
}
img{
    width: 150px;
    height: 200px;
}
.footer{
    font-weight: bold;
    font-size: small;
    margin-top: 600px;
    margin-left: 200px;
}

script.js

function func1()
{
    document.getElementById("t1").style.height=300;
    document.getElementById("t1").style.width=300;
}
function func2()
{
    document.getElementById("t2").style.height=300;
    document.getElementById("t2").style.width=300;
}
function func3()
{
    document.getElementById("t3").style.height=300;
    document.getElementById("t3").style.width=300;
}
function func4()
{
    document.getElementById("t4").style.height=300;
    document.getElementById("t4").style.width=300;
}

## OUTPUT:

![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
