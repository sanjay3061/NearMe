# Ex04 Places Around Me
## DATE: 31.10.23

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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HOME</title>
</head>
<img src="c:\Users\SEC\Pictures\Screenshots\map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Bus stand" title="Bus stand" href="bus.html" coords="1597,391,50" shape="circle">
    <area target="" alt="theater" title="theater" href="theater.html" coords="1450,618,50" shape="circle">
    <area target="" alt="hospital" title="hospital" href="hospital.html" coords="1071,728,93" shape="circle">
    <area target="" alt="school" title="school" href="school.html" coords="1107,450,67" shape="circle">
    <area target="" alt="Marriage hall" title="Marriage Hall" href="marriage.html" coords="1023,328,42" shape="circle">
</map>
</body>
</html>
```
```
bus.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>BUS STAND</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>CHEYYAR</b></font>
</h1>
<h3 align="center">
<font color="green"><b>BUS STAND</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<font face="Arial" size="5">
<b>
One of most friendly busstand ever seen,
And all kind of bus you can get here include air buses and also budget friendly buses also.
The time office in busstand the staff are very friendly and answer very gently to the passenger.
And the main thing is to hat's off to the busstand police they have doing there duty well✨.There are a lot of buses from kanchipuram and chennai.
It had good connectivity. It's generally crowded and theft is normal so be careful.. there is washroom at the end. Small eateries are good. The guy opposite to entrance sell chips and it's good
</b>
</font>
</p>
</body>
</html>
```
```
theater.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>V.A.B Theatre</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>CHEYYAR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>V.A.B Theatre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The finest theatre in cheyyar which gives an amazing cinematic experience. The seats are good with a good amount of leg room. Nice ambience,good snacks and drinks and impeccably clean. When it comes to pricing, the highest priced theatre in town. But yeah! The experience justifies the cost.One&only Muliplex in DPI,Comfortable seats,Neat and clean. Executives are so humble Excellent picture and sound quality,Screen (1) & (2) is the biggest screen with 4k Dolby Atmos audio 🔊.Screen (3,4&5) are small screen with 2k 7.1 audio 🔊.Snacks is little bit costly but it's okay to spend in a good place. …
</font>
</p>
</body>
</html>
```
```
hospital.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Government District Head Quarters Hospital</title>
</head>
<body bgcolor="gray">
<h1 align="center">
<font color="black"><b>CHEYYAR</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Government District Head Quarters Hospital</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Tahoma" size="5">
1)Here ICU has centralized oxygen supply, ventilators and high-technology life saving equipment.<br>
2)Our Operation Theatre Complex is equipped with the state-of-art Phillips C-arm Fluroscope. <br>
3)This enables us to perform spinal, brain and complex ortho surgeries. The 3-Chip Laproscope enables us to do micro-invasive, pin-hole surgeries.</font>
 </p>
</body>
</html>

```
```
school.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>CHEYYAR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of CHEYYAR Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```
```
marriage.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Marriage Hall</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHEYYAR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Marriage Hall</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Arial" size="5">
<b>
Its located at middle of cheyyar, on the way to bus stand. Its a decent marriage hall and can hold a capacity of 500 to 750, with the dining hall at the ground floor.A good place to celebrate wedding ceremonies and functions with lots of friends and families get-together.It is an ideal venue for weddings, engagements, house calls, etc. All kinds of facilities are included. The road is conveniently located.A wedding anniversary is the celebration of love, trust, partnership, tolerance, and tenacity.
</b>
</font>
</p>
</body>
</html>
```

## OUTPUT
![image](https://github.com/sanjay3061/NearMe/assets/121215929/8d34adc9-7df8-4628-bf72-78d685aaaf19)

![Screenshot (9)](https://github.com/sanjay3061/NearMe/assets/121215929/1dd12ee4-cb61-404b-961e-e56a559a719a)
![Screenshot (7)](https://github.com/sanjay3061/NearMe/assets/121215929/6550dbc8-1452-4f83-83f5-34c150b3926a)
![Screenshot (10)](https://github.com/sanjay3061/NearMe/assets/121215929/66d1e084-b631-43ff-9476-3da5b2ccc0c7)
![Screenshot (5)](https://github.com/sanjay3061/NearMe/assets/121215929/ae98b1b5-2da2-44b9-9226-903aeff42599)
![Screenshot (6)](https://github.com/sanjay3061/NearMe/assets/121215929/af0da331-1c52-44a4-b00d-25ddc6020c8e)









## RESULT
The program for implementing image maps using HTML is executed successfully.
