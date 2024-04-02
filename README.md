# Ex04 Places Around Me
## Date: 01.04.2024

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
static.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center"
        <font colur="red"><b>srivilliputtur</b></font>
    </h1>
    <h3 align="center"
    <font colour="blue"><b>Saikumar s (212222240087)</b></font>
</h3>
<center>
    <img src="map2.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="srivilliputtur arulmugu andal samethai" title="srivilliputtur arulmugu andal samethai" href="andal.html" coords="951,565,1147,651" shape="rect">
    <area target="" alt="kottapatti" title="kottapatti" href="kottapatti.html" coords="776,442,98" shape="circle">
    <area target="" alt="shri vaidyanatha swamy temple" title="shri vaidyanatha swamy temple" href="temple.html" coords="954,681,998,778,914,789,998,719,948,700,1013,769,928,796,881,706,994,711,822,753" shape="poly">
    <area target="" alt="ajay residency" title="ajay residency" href="hotel.html" coords="1145,488,1342,533" shape="rect">
    <area target="" alt="revathi cinemas a\c" title="revathi cinemas a\c" href="cinema.html" coords="874,208,103" shape="circle">
</map>
</center> 
</body>
</html>

hotel.html

<html>
<head>
<title>Hotel</title>
</head>
<body bgcolor="green">
<h1 align="center"> 
<font color="blue "><b>Srivilliputtur</b></font>
</h1>
<h3 align="center">
<font color="green"><b>hotel</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
</html>
<font face="Georgia" size="5">
    Ajay Residency in Srivilliputhur is a comfortable and affordable accommodation option that promises a pleasant stay.
    The friendly and welcoming staff ensure that guests feel at home throughout their visit. The clean and well-maintained rooms offer a cozy atmosphere,
    ideal for relaxation after a day of exploring the area. The residency's convenient location provides easy access to nearby attractions and amenities, making it a popular choice among travelers.
    Guests can enjoy delicious local cuisine at the on-site restaurant, adding to the overall experience. The peaceful ambiance of Ajay Residency makes it a perfect place for a relaxing getaway
     away from the hustle and bustle of city life. The management is attentive to guest needs, ensuring a memorable and enjoyable stay for every visitor.
     With its value for money and positive guest experiences,
     Ajay Residency is a preferred choice for accommodation in Srivilliputhur.
</p>
</body>
</html>

temple.html

<html>
<head>
<title>kovil</title>
</head>
<body bgcolor="purple">
<h1 align="center"> 
<font color="blue "><b>Srivilliputtur</b></font>
</h1>
<h3 align="center">
<font color="green"><b>temple</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
</html>
<font face="Georgia" size="5">
    The Shivan Temple in Srivilliputhur, Tamil Nadu, is a revered Hindu temple dedicated to Lord Shiva.
    Located in the heart of the town, the temple is known for its ancient architecture and spiritual significance.
    The main deity of the temple is Lord Shiva, worshipped in the form of a lingam.
    The temple complex also houses shrines dedicated to other deities, including Lord Ganesha and Goddess Parvati.
    The temple attracts devotees and tourists alike, who come to seek blessings and admire its architectural beauty.
    The temple is particularly crowded during festivals like Maha Shivaratri, when special prayers and rituals are conducted.
    The serene ambiance and religious fervor make the Shivan Temple a must-visit destination in Srivilliputhur.
</p>
</body>
</html>

kottapatti.html

<html>
<head>
<title>town</title>
</head>
<body bgcolor="">
<h1 align="center"> 
<font color="blue "><b>Srivilliputtur</b></font>
</h1>
<h3 align="center">
<font color="green"><b>lottapatti</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
</html>
<font face="Georgia" size="5">
    Kottapatti is a quaint village located near Srivilliputhur in the Virudhunagar district of Tamil Nadu, India.
    Known for its serene surroundings and lush greenery, Kottapatti offers a peaceful retreat away from the hustle and bustle of city life.
    The village is predominantly agrarian, with farming being the primary occupation of the residents.
    The fertile soil and favorable climate support the cultivation of various crops, including paddy, sugarcane, and bananas.
    Kottapatti is also known for its rich cultural heritage, with traditional festivals such as Pongal and Diwali being celebrated with great enthusiasm.
    The village has a close-knit community, and its temples are integral to its religious and cultural life.
    Accessible by road, Kottapatti provides a glimpse into rural life in Tamil Nadu and offers a tranquil environment for visitors to enjoy.
</font>
</p>
</body>
</html>

andal.html

<html>
<head>
<title>Temple</title>
</head>
<body bgcolor="grey">
<h1 align="center"> 
<font color="blue "><b>Srivilliputtur</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Andal temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
    The Srivilliputhur Andal Temple in Srivilliputhur, a town in Virudhunagar district in the South Indian state of Tamil Nadu, is dedicated to the Hindu god Vishnu. 
    It is located 80 km from Madurai.
    Constructed in the Dravidian style of architecture,
    the temple is glorified in the Nalayira Divya Prabandham, the early medieval Tamil canon of the Alvar saints from the 6th–9th centuries CE.
    It is one of the 108 Divya Desams dedicated to Vishnu, who is worshipped as Vatapatrasayi and his consort Lakshmi as Andal.
    It is believed to be the birthplace of two of the Alvars, namely Periyalvar and his foster-daughter, Andal.
</font>
</p>
</body>
</html>

cinema.html

<html>
<head>
<title>theatre</title>
</head>
<body bgcolor="yellow">
<h1 align="center"> 
<font color="blue "><b>Srivilliputtur</b></font>
</h1>
<h3 align="center">
<font color="green"><b>cinema</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
</html>
<font face="Georgia" size="5">
    Revathi Cinema in Srivilliputhur is a popular movie theater that offers a great cinematic experience for residents and visitors alike.
    The theater is known for its comfortable seating, excellent sound system, and high-quality projection, ensuring that guests enjoy every moment of the movie.
    The cinema screens a mix of regional and Bollywood films, catering to a wide audience.
    The staff at Revathi Cinema are friendly and helpful, adding to the overall positive experience.
    The theater's convenient location makes it easily accessible for moviegoers.
    The ticket prices at Revathi Cinema are reasonable, making it an affordable entertainment option.
    Overall, Revathi Cinema is a great place to unwind and enjoy a movie with friends and family in Srivilliputhur.
</p>
</body>
</html>
```



## OUTPUT

![alt text](<Screenshot 2024-04-02 185023.png>)

![alt text](<Screenshot 2024-04-02 190701.png>)

![alt text](<Screenshot 2024-04-02 190048.png>)

![alt text](<Screenshot 2024-04-02 185556.png>)

![alt text](<Screenshot 2024-04-02 184925.png>)

![alt text](<Screenshot 2024-04-02 191044.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
