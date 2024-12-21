# Ex04 Places Around Me
## Date: 21/12/2024

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
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Attur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>S S SHARVESHWARAN (24900901)</b></font>
</h3>
<center>
<img src="map.png.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700, 250, 850,400" href="map.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="bus.html" title="BUS STAND">
<area shape="circle" coords="540, 200, 30" href="temple.html" title="KAYANIRMALESWARAR TEMPLE">
<area shape="rect" coords="600, 200, 700,500" href="hall.html" title="VISHNU PRIYA">
<area shape="rect" coords="950, 120, 1100, 140" href="rail.html" title="RAILWAY STATION">
</map>
</center>
</body>
</html>
home.html
<html>
<head>
<title>ATTUR</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="red"><b>SALEM DISTRICT</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ATTUR TALUK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Attur or Aathur is a municipality and headquarters of Attur taluk in the Salem district in the state of Tamil Nadu, India. As of the 2011 census, the town had a population of 61,793. Attur is growing economically.Attur assembly constituency is part of Kallakurichi (Lok Sabha constituency).[6] Jayashankar is the current Member of Tamil Nadu Legislative Assembly (MLA) representing the Attur constituency as of 2021.
</body>
</html>
bus.html
<html>
<head>
<title>BUS STAND</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="yellow"><b>KAMARAJAR NEW BUS STAND</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
There are many boarding and dropping points in Attur, including Attur and Gandhipuram. Most boarding points have amenities like waiting rooms, washrooms, cafes, and restaurants. 
Attur is a town in the Salem District of Tamil Nadu. It's located at the junction of NH 79 and NH 136, and one national highway and two state highways originate from there. 
</p>
</body>
</html>
temple.html
<html>
<head>
<title>SRI KAYANIRMALESWARAR TEMPLE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="BLACK"><b>GODDNESSS OF AGILANDESHWARI</b></font>
</h1>
<h3 align="center">
<font color="red"><b>GOOD</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
There is a five-tiered Raja Gopuram facing east. Next to the front hall is Nandi. In this temple there are many Vinayakas, lord of grace in panchabhuta places, Lord Murugan with Goddess Valli, Chatur Puja Bhairava, Ash Puja Bhairava, Suvarna Agarshana Bhairava, Mahalakshmi, Saraswati, Dakshinamurthy, Lingotpavar, Brahma, Durgai, Ayyappan, Surya, Saneesuvaran. and Nagas. There is also a Hanuman shrine. During the Deeparathana, the light of the lamp is beautifully displayed on the Linga Thirumeni.
</p>
</body>
</html>
hall.html
<html>
<head>
<title>VISHNU PRIYA </title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>MRRIAGE HALL</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>GOOD INFRASTRUCTURE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Sri Vishnu Priya Marriage Hall is a banquet hall located in Attur, Tamil Nadu. The average rating of this place is 3.90 out of 5 stars based on 57 reviews. The street address of this place is HHXX+M2M, Pungavadi Puthur, Attur, Tamil Nadu 636102, India. It is about 0.22 kilometers away from the Attur railway station.Attur railway station is the nearest railway station to Sri Vishnu Priya Marriage Hall. It is nearly 0.22 kilometers away from it.
</body>
</html>
rail.html
<html>
<head>
<title>RAILWAY STATION</title>
</head>
<body bgcolor="black">
<h1 align="center">
<font color="white"><b>attur main junction</b></font>
</h1>
<h3 align="center">
<font color="white"><b>good place</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5" color="white">
The station came into existence as part of the Chennai (then Madras)–Beypore (present-day Kerala) rail line in the 1860s. The station gained its junction status when the metre-gauge line was laid to Vridachalam, providing a connection to the South Indian railway network. After independence, the abandoned narrow-gauge line of Dharmapuri–Morappur was re-built and alignment changed to terminate the line at Salem Junction instead of Morappur. It was upgraded to metre gauge simultaneously. Salem to Bangalore via Hosur 124-mile-long railway line survey was sanctioned on 25 July 1955 and field work started on 27 February 1956
</p>
</body>
</html>
```



## OUTPUT

![alt text](<Screenshot 2024-12-21 133304.png>)
![alt text](<Screenshot 2024-12-21 133331.png>)
![alt text](<Screenshot 2024-12-21 133350.png>)
![alt text](<Screenshot 2024-12-21 133407.png>)
![alt text](<Screenshot 2024-12-21 133435.png>)
![alt text](<Screenshot 2024-12-21 134027.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
