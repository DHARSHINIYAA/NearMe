# Ex04 Places Around Me
## Date: 26.3.2024

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
![Screenshot 2024-04-04 084757](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/e7d250dc-42ad-44f8-b4da-5c07e5e6bae8)
![Screenshot 2024-04-04 084823](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/400fbc61-53c4-4d53-be63-5057a538fc63)
![Screenshot 2024-04-04 085016](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/c3b15acf-f8e9-4cfd-9c98-d95d9da9c0a7)
![Screenshot 2024-04-04 085043](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/c376df7b-92b8-4d48-9fab-d36a196707ba)
![Screenshot 2024-04-04 085400](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/5bcd99a0-62c7-4db3-b6c4-4fc3840c9295)
![Screenshot 2024-04-04 090357](https://github.com/DHARSHINIYAA/NearMe/assets/149560172/2de7733b-0d2f-410f-9aea-2ae232e1293a)




## RESULT
The program for implementing image maps using HTML is executed successfully.
