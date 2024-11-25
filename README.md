# Ex04 Places Around Me
## Date: 25.11.2024

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
map.html

map.html
<html>
<head>
<title>MyCity</title>
</head>
<body>
<h1 align="center">
<font color="purple"><b>AMBUR</b></font>
</h1>
<h3 align="center">
<font color="lavender"><b>PRAISY NISHITHA(24900090)</b></font>
</h3>
<center>
   <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="AMBUR" title="AMBUR" href="ambur.html" coords="495,496,608,579" shape="rect">
        <area target="" alt="PRIYA MAHAL" title="PRIYA MAHAL" href="priya.html" coords="240,761,388,816" shape="rect">
        <area target="" alt="STAR BIRIYANI" title="STAR BIRIYANI" href="star.html" coords="764,190,559,286" shape="rect">
        <area target="" alt="SWIMMING POOL" title="SWIMMING POOL" href="pool.html" coords="987,574,93" shape="circle">
        <area target="" alt="GANDHI NAGAR" title="GANDHI NAGAR" href="gandhi.html" coords="671,420,732,429,792,429,783,519,667,484,639,459" shape="poly">
    </map>
</center>
</h3>
</body>
</html>

ambur.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="green"><b>AMBUR</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>THE AMBUR</b></font>
</h3>
<hr size="5" color="cyan">
<p align="justify">
<font face="Georgia" size="7" color="white">
    Ambur is a town and municipality in newly announced Tirupathur district, Vellore region of Tamil Nadu, India. It is located on the banks of the Palar River
</font>
</p>
</body>
</html>

gandhi.html

<html>
<head>
<title>GANDHI NAGAR</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="purple"><b>STREET</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>BUSY STREET</b></font>
</h3>
<hr size="3" color="cyan">
<p align="justify">
<font face="Georgia" size="5" color="green">
    Ambur Leather Store in Gandhi Nagar West,Vellore listed under Leather Accessory Dealers
</font>
</p>
</body>
</html>

pool.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="purple"><b>SWIMMMING POOL</b></font>
</h1>
<h3 align="center">
<font color="pink"><b> OLD BETHELHEM</b></font>
</h3>
<hr size="3" color="cyan">
<p align="justify">
<font face="Georgia" size="5" color="white">
    Specially designed swimming pools are also used for diving, water sports, and physical therapy
</font>
</p>
</body>
</html>

priya.html

<html>
<head>
<title>AMBUR</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="purple"><b>MAHAL</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>PRIYA MAHAL</b></font>
</h3>
<hr size="3" color="cyan">
<p align="justify">
<font face="Georgia" size="5" color="white">
    Priya Mahal in M C Road, Ambur is a top player in the category Banquet Halls in the Ambur. This well-known establishment acts as a one-stop destination
</font>
</p>
</body>
</html>

star.html

<html>
<head>
<title>AMBUR</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="purple"><b>THE AMBUR FAMOUS</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>STAR BIRIYANI</b></font>
</h3>
<hr size="3" color="cyan">
<p align="justify">
<font face="Georgia" size="5" color="white">
    Ambur biryani is a delightful one-pot meal with succulent pieces of meat cooked to perfection along with the aromatic jeera samba rice, mint leaves, coriander leaves and whole spices
</font>
</p>
</body>
</html>


## OUTPUT
Screenshot 2024-11-25 094205.png
Screenshot 2024-11-25 094220.png
Screenshot 2024-11-25 094233.png
Screenshot 2024-11-25 094250.png
Screenshot 2024-11-25 094305.png
screenshot 2024-11-25 094148.png

## RESULT
The program for implementing image maps using HTML is executed successfully.
