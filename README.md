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
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <front color="purple"><b>Erode</b></front>
        </h1>
        <h3 align="center">
            <front color="blue"><b>DHARSHINIYAA KS (212223100004)</b></front>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map" >

<map name="image-map">
    <area target="" alt="Hotel Atrium" title="Hotel Atrium" href="hotel.html" coords="810,517,938,566" shape="rect">
    <area target="" alt="medical center hospital" title="medical center hospital" href="medical.html" coords="500,590,61" shape="circle">
    <area target="" alt="Vaikal medu bus stop" title="Vaikal medu bus stop" href="busstop.html" coords="662,731,850,792" shape="rect">
    <area target="" alt="Annapoorani theatre" title="Annapoorani theatre" href="theatre.html" coords="733,60,77" shape="circle">
    <area target="" alt="inn resort" title="inn resort" href="inn.html" coords="84,451,223,519" shape="rect">
</map>
        </center>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-04-04 084757.png>)
![alt text](<Screenshot 2024-04-04 085400.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
