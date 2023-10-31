# Ex04 Places Around Me
## Date : 21/10/23
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
# map.html
```
<html>

<head>
    <title> Image Map </title>
</head>

<body>
    <h1 align="center">
        <font color="red"><b>Anna University</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Places Around Me</b></font>
    </h3>
    <center>
        <img src="map.jpg" usemap="#MyCity" height="420" width="1100">
        <map name="MyCity">
            <area shape="circle" coords="190,50,20" href="annauniv.html" title="Anna University">
            <area shape="rectangle" coords="230,30,260,60" href="mit.html" title="Madras Institute">
            <area shape="circle" coords="400,350,50" href="park.html" title="Guindy National Park">
            <area shape="circle" coords="400,200,75" href="temple.html”  title=" Kailash Temple">
            <area shape="rectangle" coords="490,150,870,320" href="bus.html" title="bus stand">
        </map>
    </center>
</body>
</html>
```
# annauniv.html
```
<html>
<head>
<title>Anna University</title>
</head>
<body bgcolor="lime">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Anna University</h3>
<hr size="3" color="red">
<p align="justify">
Excellent University for doing Engineering Courses
</p>
</body>
</html>
```
# bs.html
```
<html>
<head>
<title>Bus stand</title>
</head>
<body bgcolor="orange">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Bus Stand</h3>
<hr size="3" color="red">
<p align="justify">
A well-equipped bus stop where all the MTC buses and share autos will stop.
</p>
</body>
</html>
```
# mit.html
```
<html>
<head>
<title>Madras Institute of Technology</title>
</head>
<body bgcolor="yellow">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Madras Institute of Technology</h3>
<hr size="3" color="red">
<p align="justify">
Best place for studying UG and PG courses.
</p>
</body>
</html>
```
# park.html
```
<html>
<head>
<title>Guindy National Park</title>
</head>
<body bgcolor="cyan">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Guindy National Park</h3>
<hr size="3" color="red">
<p align="justify">
Nice Park.
</p>
</body>
</html>
```
# temple.html
```
<html>
<head>
<title>Kailash Temple</title>
</head>
<body bgcolor="pink">
<h1 align="center">Places Around Me</h1>
<h3 align="center">Kailasanathar Temple</h3>
<hr size="3" color="red">
<p align="justify">
Kailasanathar temple is situated near Anna University on the banks of River Adyar.
</p>
</body>
</html>
```

## OUTPUT
![ot1](https://github.com/Dhiyanesh24/NearMe/assets/118362288/2c6c1097-7af8-4015-85e0-1a7b65fe1473)

![ot2](https://github.com/Dhiyanesh24/NearMe/assets/118362288/f9a3b5e4-f260-4b36-b892-cfd40e813286)

![ot3](https://github.com/Dhiyanesh24/NearMe/assets/118362288/52fbaf7a-33d7-445e-bff3-3057d50b419f)

![ot4](https://github.com/Dhiyanesh24/NearMe/assets/118362288/90a57eec-c029-419e-ad91-2a32c83ca2aa)

![ot5](https://github.com/Dhiyanesh24/NearMe/assets/118362288/e7e7a469-b974-4969-a05a-7530aa6bf639)

![ot6](https://github.com/Dhiyanesh24/NearMe/assets/118362288/19913f29-236f-4b42-9a80-6c3bbab215c8)

![ot7](https://github.com/Dhiyanesh24/NearMe/assets/118362288/545e4117-01dd-48a0-a6ff-3aa51f303ef0)

## RESULT
The program for implementing image maps using HTML is executed successfully.
