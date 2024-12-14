# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<html>
<head>
<title>South korea</title>
</head>
<body>
<h1 align="center">
<font color="pink"><b> Busan</b></font>
</h1>
<h2 align="center">
<font color="purple"><b>Avanthykkha.A.G (24006077)</b></font>
</h2>
<img src="c:\Users\admin\Pictures\Screenshots\map.p.png" usemap="#image-map" height='610' width='1450'>
<map name="image-map">
<area target= "231,393,232,485" alt="Sila University" title="Sila University" href="silauni.htm">
<area target="1592,272,1372,292" alt="Jangsan Waterfall" title="jangsan imagemap.htm">
<area target="1621,539,1431,557" alt="SEALIFE Busan Aquarium" title="Sealife imagemap.htm">
<area target="821,468,1037,457" alt="Jeonpo Café Street" title="Jeonpo Café Street" href="jenpo cafe.htm">
<area target="648,187,860,174"" alt="Busan Aisad Main Stadium" title="Busan Aisad Main Stadium " href="Stadium.htm">
</map>
</body>
</html>
```
```
silauni.html
<html>
<head>
<title>Sila University</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="gray"><b>Busan</b></font>
</h1>
<h3 align="center">
<font color="black"><b>Sila University</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<front face="" size="S">
    "Silla University (Korean: 신라대학교) is a private university located in the second largest city of Busan, South Korea. To encourage international careers, collaborations and exchanges, Silla University maintains strong international links with 175 universities in 28 countries.
    A beautiful campus by the sea and the foot of the Baekyang mountain, Silla University first opened its doors to students in Busan, South Korea, in 1954. Today, the university is home to nearly 11,000 students, nine colleges, four graduate schools and offers over 60 majors."
   <br>
   
    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 143109.png"
    <p>
</body>
</html>
```
```
jangsan imagemap.html
<html>
<head>
<title>Jangsan Waterfall</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="gray"><b>Busan</b></font>
</h1>
<h3 align="center">
<font color="black"><b>Jangsan Waterfall</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<front face="" size="S">
    "Jangsan Mountain, overlooking the southern sea, is a towering natural wonder, with a wide range of hiking trails. Enjoy a 3 hr outing to the peak of Jangsan Mountain while appreciating the scenic view of Haeundae Marine City and Gwangandaegyo Bridge.
    Daecheon Park is where most people start their hike. The starting point from the park to enter the valley is flat and well formed, so you can embark on the hike smoothly. While passing through the forest park, fill yourself with the freshness of nature. Hike slowly as you stroll along a gentle valley path.
    hortly after, you’ll see a small temple called “Pokposa Temple.” Look around inside Daeungjeon Hall, and turn back to the trail. The uphill part begins after you pass Yangun Falls, with its white waterfall and blue pond beneath. Then soon, you’ll cross Sinseongyo Bridge."
   <br>
    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 144239.png">
    <p>
</body>
</html>
```
```
Sealife imagemap.html
<html>
<head>
<title>SEALIFE Busan Aquarium </title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="gray"><b>Busan</b></font>
</h1>
<h3 align="center">
<font color="black"><b>SEALIFE Busan Aquarium </b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<front face="" size="S">
    Sea Life Busan features many captivating underwater world such as the Sea Turtle Rescue Team for experiential activities or the Sea at night zone which uses world-class digital technology.
     The aquarium's multiple exhibits are sure to delight everyone.Sea Life Busan Aquarium is an aquarium located in Haeundae Beach, Busan, South Korea. It first opened on November 7, 2001. Sea Life Busan Aquarium.
    <br>
    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-07 143109.png">
    <p>
</body>
</html>
```
```
jenpo cafe.html
<html>
<head>
<title>Jeonpo Café Street </title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="gray"><b>Busan</b></font>
</h1>
<h3 align="center">
<font color="black"><b>Jeonpo Café Street </b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<front face="" size="S">
    Jeonpo Café Street is a unique and vibrant street lined with diverse cafés.From specialty coffee shops to dessert cafés, bakeries, and brunch spots, visitors can choose from a wide range of options to suit their preferences.
    A wide range of cafes, including dessert cafes, specialty coffee shops, and brunch spots. The cafes are housed in a variety of spaces, including renovated houses, factories, and warehouses
    <br>
    <img src="c:\Users\admin\Desktop\math exp\Jeonpo-Cafe-Street imap.jpg">
    <p>
</body>
</html>
```
```
Stadium.html
<html>
<head>
<title> Busan Aisad Main Stadium</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="gray"><b>Busan</b></font>
</h1>
<h3 align="center">
<font color="black"><b> Busan Aisad Main Stadium </b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<front face="" size="S">
    It was built for the 2002 Asian Games and was also used for matches at the 2002 FIFA World Cup. It has a capacity of 53,769. 
    The stadium hosted the opening and closing ceremonies of the 2002 Asian Games and was also the venue of athletics events during the games. It is the home venue of the K League club Busan IPark.
    <br>
    <img src="c:\Users\admin\Desktop\math exp\stadium.jpg">
    <p>
</body>
</html>
```

# OUTPUT
![Screenshot 2024-12-14 135754](https://github.com/user-attachments/assets/95437039-5f83-4586-8c5b-d5ef65d76c59)
![Screenshot 2024-12-14 135817](https://github.com/user-attachments/assets/5ca129a3-f94a-476e-9128-be5b405bf4ee)
![Screenshot 2024-12-14 135928](https://github.com/user-attachments/assets/849c650a-b729-405f-a4c9-cfc245f02feb)
![Screenshot 2024-12-14 135956](https://github.com/user-attachments/assets/806b7657-e26d-4ba9-b6d3-8c7298e09347)
![Screenshot 2024-12-14 140543](https://github.com/user-attachments/assets/d176dce5-f4f5-4776-8adb-257df3054494)
![Screenshot 2024-12-14 140618](https://github.com/user-attachments/assets/c2217cc2-c564-4aa6-b7ef-6c8dea137a56)



# RESULT
The program for implementing image maps using HTML is executed successfully.
