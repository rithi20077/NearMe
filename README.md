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
 imagemap.html
<html>
    <head>
        <title>Image Mapping</title>
    </head>
    <body>
        <style>
            img{
                width: 1500px;
            }
        </style>
        <img src="map.jpg" usemap="#mapping"/>
        <map name="mapping">
            <area shape="poly" coords="283,331,373,328,377,372,288,373" href="fc.html" title="Food Court">
            <area shape="poly" coords="512,395,627,391,632,446,519,440" href="saveetha.html" title="Saveetha">
            <area shape="poly" coords="744,267,927,258,935,324,742,318" href="evp1.html" title="EVP Cinemas">
            <area shape="poly" coords="690,444,864,444,855,510,679,504" href="queensland.html" title="Queens Land">
            <area shape="poly" coords="465,898,651,894,652,953,464,963" href="royal.html" title="Royal Chitiran">
        </map>
    </body>
</html>

evp1.html
<html>
    <head>
        <title>EVP Cinemas</title>
    </head>
    <center>
        <img src="evp.jpg" height="150px" width="150px">
    </center><hr>
    <body style="background-color: bisque;">
        <style>
            p{
                font-size: x-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
            li{
                font-size: x-large;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
        </style>
    <h1>About</h1>
    <p>
        Feel the action come alive with ICE, IMAX, and 4DX Screens. 
        Book Your Tickets Now! Enjoy the Latest Movies with Great Deals on Movie Tickets. 
        Book Tickets! Book Movie Tickets. Check Showtimes Near You. Pre-Book F&B. View Trailers. Ultimate Movie Experience.
    </p>
    <h1>Now Showing</h1>
    <ul class="Now Showing">
        <li>Amaran</li>
        <li>Pushpa 2</li>
        <li>Lucky Baskar</li>
        <li>Sorgavasal</li>
        <li>ZEBRA</li>
    </ul>
    <h1>Coming Soon</h1>
    <ul class="Coming Soon">
        <li>Kraven The Hunter</li>
        <li>Miss You</li>
        <li>HERETIC</li>
        <li>The lord of the Rings</li>
        <li>Zero se Restart</li>
    </ul>
    <h1>Contact Us</h1>
        <p1 style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: larger;">Address :- <br>Santhosha Nagar, Chennai - Bangalore, National Highway, Chembarambakkam, Tamil Nadu 600123.<br>
            🕿 :- 044 7777 5544
        </p1>
        <h3 style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">2024 &copy; All rights reserved</h3>
    </body>
</html>
```

## OUTPUT

IMAGE MAP
![WEB 4-1](https://github.com/user-attachments/assets/27182399-f14f-4c1f-b355-38c5d7920b3b)

Saveetha
![saveetha](https://github.com/user-attachments/assets/35d90bf9-9b64-41b3-b3b5-47bcb1603237)

EVP
![EVP](https://github.com/user-attachments/assets/acb83542-37c7-4b8b-b93d-2e0caa04e1a8)

## RESULT
The program for implementing image maps using HTML is executed successfully.
