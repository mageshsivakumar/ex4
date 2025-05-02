# Ex04 Places Around Me
## Date: 02/05/25

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
home.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>MAGESH S</b></font>
        </h3>
        <center>
           
            <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="NEW BUS STAND" title="NEW BUS STAND" href="busstand.html" coords="450,685,655,746" shape="rect">
    <area target="" alt="ES HOSPUTAL" title="ES HOSPUTAL" href="hospItal.html" coords="683,413,844,491" shape="0">
    <area target="" alt="KALYAN CINEMAS" title="KALYAN CINEMAS" href="theatre.html" coords="730,333,902,400" shape="0">
    <area target="" alt="VILLUPURAM JUNCTION" title="VILLUPURAM JUNCTION" href="junction.html" coords="1256,236,1426,287" shape="0">
    <area target="" alt="ANNA GOVT COLLEGE" title="ANNA GOVT COLLEGE" href="college.html" coords="1650,207,1778,260" shape="0">
</map>
        </center>  
    </body>
</html>

busstand.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>NEW BUS STAND</b></font>
        </h2>
        <br>
        <hr size="3" color="red">
        <br>
        <center>
            <img src="bus.jpeg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Villupuram New Bus Stand, inaugurated in 2000, is a major transport hub in Tamil Nadu. Located on NH 45 near the Collectorate, it spans 15 acres and features 68 bus bays, shops, hotels, waiting halls, and parking facilities. It serves as a key junction for buses connecting Tamil Nadu and neighboring states.
                
            </font>
        </p>
    </body>
</html>

hospital.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>ES HOSPITAL</b></font>
        </h2>
        <br>
        <hr size="3" color="red">
        <br>
        <center>
            <img src="hosp.jpeg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                ES Hospital in Villupuram is a multi-specialty healthcare facility offering comprehensive medical services across various disciplines, including cardiology, neurology, orthopedics, and gynecology. Established in 2007, it is equipped with modern infrastructure and provides 24/7 emergency care. The hospital is located at No. 32-B, Trichy Trunk Road, Villupuram, Tamil Nadu 605602
                
            </font>
        </p>
    </body>
</html>

theatre.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>KALYAN CINEMAS</b></font>
        </h2>
        <br>
        <hr size="3" color="red">
        <br>
        <center>
            <img src="cine.jpeg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Kalyan Cinemas A/C DTS is a popular movie theatre located in KK Nagar, Villupuram, Tamil Nadu. Situated on NH 45A, it offers air-conditioned auditoriums with DTS sound systems, providing a comfortable viewing experience for moviegoers. The theatre screens a variety of films, including regional, Bollywood, and Hollywood movies, catering to diverse audiences. Tickets can be conveniently booked online through platforms like Paytm and TicketNew.
                
            </font>
        </p>
    </body>
</html>

junction.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>VILLUPURAM JUNCTION</b></font>
        </h2>
        <br>
        <hr size="3" color="red">
        <br>
        <center>
            <img src="junc.jpeg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Villupuram Junction (station code: VM) is a major railway hub in Tamil Nadu, connecting Chennai to southern and central parts of the state. It features six platforms and handles over 190 trains daily, serving as a key transit point in the Southern Railway zone
            </font>
        </p>
    </body>
</html>

college.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VILLUPURAM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>ANNA ARTS COLLEGE</b></font>
        </h2>
        <br>
        <hr size="3" color="red">
        <br>
        <center>
            <img src="clg.jpeg" alt="" height="400" width="600">
        </center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Arignar Anna Government Arts College, Villupuram, established in 1968, is a public institution offering undergraduate and postgraduate programs in arts, science, and commerce. Affiliated with Thiruvalluvar University and recognized by the UGC, the college provides a range of courses including Tamil, English, History, Economics, Physics, Chemistry, Mathematics, Computer Science, and more. Located in Villupuram, Tamil Nadu, it serves as a significant center for higher education in the region. 
                
            </font>
        </p>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (7).png>)
  
 ![alt text](<Screenshot (3).png>) 
 ![alt text](<Screenshot (4).png>) 
 ![alt text](<Screenshot (5).png>) 
 ![alt text](<Screenshot (6).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
