# Ex04 Places Around Me
## Date:26/03/24

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
## map.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<h3><center>PRASANNA L(212221040130)</center></h3>
<hr>
</head>
<body bgcolor="WHITE">
<img src="map.png" usemap="#image-map" >
<map name="image-map">
    <area target="" alt="Thiruvallur nagar" title="Thiruvallur nagar" href="Vallur.html" coords="217,64,433,158" shape="rect">
    <area target="" alt="Sammandapuram" title="Sammandapuram" href="puram.html" coords="409,464,561,471,561,382,392,382" shape="poly">
    <area target="" alt="Lakshmipuram" title="Lakshmipuram" href="lakshmi.html" coords="1031,384,59" shape="circle">
    <area target="" alt="Rajapalayam" title="Rajapalayam" href="rjpm.html" coords="680,440,853,522" shape="rect">
    <area target="" alt="Panchu Market" title="Panchu Market" href="market.html" coords="910,218,54" shape="circle">
</map>
</body>
</html>

## lakshmi.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<h3><center>Lakshmipuram</center></h3>
<hr>
</head>
<body bgcolor="GREEN">
<p>
    A lakshmipuram is a Village in Vembakottai Block in Virudhunagar District of Tamil Nadu State, India. It is located 42 KM towards west from District head quarters Virudhunagar. 7 KM from Vembakottai. 582 KM from State capital Chennai
</p>
</body>
</html>

## market.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<h3><center>PANCHU MARKET</center></h3>
<hr>
</head>
<body bgcolor="blue">
<p>
    Rajapalayam New Bus Stand in Rajapalayam, Virudhunagar is a top player in the category Bus Depot in the Virudhunagar. This well-known establishment acts as a one-stop destination servicing customers both local and from other parts of Virudhunagar. Over the course of its journey, this business has established a firm foothold in it's industry. The belief that customer satisfaction is as important as their products and services, have helped this establishment garner a vast base of customers, which continues to grow by the day.

</p>
</body>
</html>

## puram.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<h3><center>Sammandhapuram</center></h3>
<hr>
</head>
<body bgcolor="Purple">
<p>
    South Sammanthapuram is a Locality in Rajapalaiyam City in Tamil Nadu State, India.
    South Sammanthapuram Pin code is 626117 and postal head office is Rajapalayam .
    
    Teachers Colony , Thoppupatti , Rajapalaiyam , Srirengapalayam , Vadakku Venganallur are the nearby Localities to South Sammanthapuram.</p>
</body>
</html>

##rjpm.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<hr>
</head>
<body bgcolor="red">
<p>
    Rajapalayam is a town in the Indian state of Tamil Nadu. It is the largest municipality in the Virudhunagar district[citation needed]. Rajapalayam is located on the Madurai to Quilon National Highway at a distance of 562 km south of the state capital Chennai. The economy is primarily industrial with several mills for spinning and weaving. The town is known for its mango and the Rajapalayam breed of dogs.
</p>
</body>
</html>

## vallur.html
<html>
<head>
<h1><center>RAJAPALAYAM</center></h1>
<h3><center>THIRUVALLUR NAGAR</center></h3>
<hr>
</head>
<body bgcolor="PINK">
<p>
    Thiruvalluvar Nagar is a small Village/hamlet in Rajapalaiyam Block in Virudhunagar District of Tamil Nadu State, India. It comes under Ayyankollankondan Panchayath. It is located 52 KM towards west from District head quarters Virudhunagar. 8 KM from Rajapalaiyam. 581 KM from State capital Chennai
</p>
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2024-03-26 213905.png>)
![alt text](<Screenshot (93).png>)
![alt text](<Screenshot (94).png>)
![alt text](<Screenshot (95).png>)
![alt text](<Screenshot (96).png>)
![alt text](<Screenshot (97).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
