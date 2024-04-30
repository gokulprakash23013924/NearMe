# Ex04 Places Around Me
## Date: 

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
```
#map.html
<html>
<head>
    <title>NEYVELI</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>GOKUL PRAKASH M (212223240041)</b></font>
    </h1>
    <img src="map1.png" alt="Workplace" usemap="#workmap" height="650" width="1465">
    <map name="workmap">
        <area shape="circle" coords="850,350,50" alt="neyveli ts" href="Neyveli T.S.html" title="neyveli ts">
        <area shape="circle" coords="750,100,50" alt="block-5" href="Block-5.html" title="block-5">
        <area shape="circle" coords="350,150,50" alt="kurnool" href="NLC General Hospital.html" title="nlc general hospital">
        <area shape="circle" coords="550,350,50" alt="tirupati" href="park.html" title="Park">
        <area shape="circle" coords="725,550,60" alt="nellore" href="guest house.html" title="Guest House">
    </map>
</body>
</html>
```
```
#park.html
<html>
    <head>
        <title>park</title>
    </head>
    <body style="background-color: rgb(123, 255, 0);">
        <center>
            <h1 style="color: rgb(167, 90, 128);letter-spacing: 2px;">Golden Jubilee Park</h1>
            <h3 style="color: white; letter-spacing: 2px;"></h3>
            <hr>
            <p style="font-size: 20px;">Golden Jubilee Park in Neyveli is one of the leading businesses in the Parks. Find Address, Contact Number, Reviews & Ratings, Photos, Maps of Golden Jubilee Park, Neyveli.</p>
        </center>
    </body>
</html>
```
```
#neyveli T.S.html
<html>
    <head>
        <title>Neyveli T.S</title>
    </head>
    <body style="background-color: rgb(255, 0, 55);">
        <center>
            <h1 style="color: rgb(24, 23, 24);letter-spacing: 2px;">Neyveli T.S</h1>
            <h3 style="color: white; letter-spacing: 2px;"></h3>
            <hr>
            <p style="font-size: 20px;">Neyveli is an industrial town in the Cuddalore district in the Indian state of Tamil Nadu. It is located 62 kilometres (39 mi) inland from the Bay of Bengal, west of Pondicherry and 197 kilometres (122 mi) south of Chennai. The town was developed in 1956 after the establishment of Neyveli Lignite Corporation, a public sector enterprise.</p>
        </center>
    </body>
</html>
```
```
#block-5.html
<html>
    <head>
        <title>block-5</title>
    </head>
    <body style="background-color: rgb(111, 0, 255);">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">block-5</h1>
            <h3 style="color: white; letter-spacing: 2px;"></h3>
            <hr>
            <p style="font-size: 20px;">
                Block 5, Neyveli T.s is a Locality in Neyveli City in Tamil Nadu State, India.
                Block 5, Neyveli T.s Pin code is 607803 and postal head office is Neyveli 3 .</p>
        </center>
    </body>
</html>
```
```
#NLC general hospital.html
<html>
    <head>
        <title>nlc general hospital</title>
    </head>
    <body style="background-color: rgb(255, 85, 0);">
        <center>
            <h1 style="color: rgb(21, 20, 21);letter-spacing: 2px;">NLC General Hospital</h1>
            <h3 style="color: white; letter-spacing: 2px;"></h3>
            <hr>
            <p style="font-size: 20px;">NLC sources say the hospital, besides catering to the health care needs of its regular employees and contract workers and their families, is offering free services to the people from the neighbouring villages.</p>
        </center>
    </body>
</html>
```
```
#guest house.html
<html>
    <head>
        <title>guest house</title>
    </head>
    <body style="background-color: rgb(255, 0, 55);">
        <center>
            <h1 style="color: rgb(31, 29, 30);letter-spacing: 2px;">Neyveli Guest House</h1>
            <h3 style="color: white; letter-spacing: 2px;"></h3>
            <hr>
            <p style="font-size: 20px;">
                Neyveli is a township in the Cuddalore district of Tamil Nadu, India, known primarily for its lignite mines and power generation facilities. Like many industrial towns, Neyveli likely has guest houses catering to visitors, especially those related to the mining and power sectors. These guest houses could serve various purposes, such as accommodating business travelers, government officials, or visitors to the area.</p>
        </center>
    </body>
</html>

```git
## OUTPUT
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (7).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (6).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
