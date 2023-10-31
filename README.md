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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HOME</title>
</head>
<img src="Screenshot 2023-10-23 203740.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Bus stand" title="Bus stand" href="bus stand.html" coords="1597,391,50" shape="circle">
    <area target="" alt="DMAX" title="DMAX" href="dmax.html" coords="1450,618,50" shape="circle">
    <area target="" alt="Ground" title="Ground" href="playground.html" coords="1071,728,93" shape="circle">
    <area target="" alt="school" title="school" href="school.html" coords="1107,450,67" shape="circle">
    <area target="" alt="Marraiage hall" title="Marraiage Hall" href="Marraige_Hall.html" coords="1023,328,42" shape="circle">
</map>
</body>
</html>
```
```html
BUS STAND.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>BUS STAND</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>DHARMAPURI</b></font>
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
And the main thing is to hat's off to the busstand police they have doing there duty well✨.There are a lot of buses from Krishnagiri and Hogenakal. We used the stand for coimbatore and Hogenakal. It had good connectivity. It's generally crowded and theft is normal so be careful.. there is washroom at the end. Small eateries are good. The guy opposite to entrance sell chips and it's good
</b>
</font>
</p>
</body>
</html>
```
```html
Theater.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>DMAX Theater</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Dharmapuri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>DMAX theater</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The finest theatre in dharmapuri which gives an amazing cinematic experience. The seats are good with a good amount of leg room. Nice ambience,good snacks and drinks and impeccably clean. When it comes to pricing, the highest priced theatre in town. But yeah! The experience justifies the cost.One&only Muliplex in DPI,Comfortable seats,Neat and clean. Executives are so humble Excellent picture and sound quality,Screen (1) & (2) is the biggest screen with 4k Dolby Atmos audio 🔊.Screen (3,4&5) are small screen with 2k 7.1 audio 🔊.Snacks is little bit costly but it's okay to spend in a good place. …
</font>
</p>
</body>
</html>
```
```html
playground.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>playground</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>DHARMAPURI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Playground</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Just a 100m walk from the main road.
hosts for various sports events , walking and many initiatives.
I was here on many occasions, my favorite is when we came here for divisional throwball event and we defeated krishnagiri team in final.
I came here for the first time when I was studying 3rd std for divisional athletics.
don't have much trees near by but the dias is huge. they literally have everything near by. the renovated basket ball courts and shuttle courts are it's pros.lot of eatery shops outside as well.do exercise everyday

</b>
</font>
</p>
</body>
</html>
```
```html
SCHOOL.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>DHARMAPURI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Dharmapuri Government Higher Secondary School are 
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
```html
Marriage Hall.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Marriage Hall</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>DHARMAPURI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Marriage Hall</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Arial" size="5">
<b>
Its located at Kumarasamipettai, on the way to District Stadium. Its a decent marriage hall and can hold a capacity of 500 to 750, with the dining hall at the ground floor.A good place to celebrate wedding ceremonies and functions with lots of friends and families get-together.It is an ideal venue for weddings, engagements, house calls, etc. All kinds of facilities are included. The road is conveniently located.A wedding anniversary is the celebration of love, trust, partnership, tolerance, and tenacity.
</b>
</font>
</p>
</body>
</html>
```

## OUTPUT
![Screenshot 2023-10-23 212133](https://github.com/jaisurya143/NearMe/assets/121999338/ede6d205-786b-4ae8-b10d-36cffb4f9e90)
![image](https://github.com/jaisurya143/NearMe/assets/121999338/a9309bfa-feec-4f62-b7fa-4a4de55f96b1)
![image](https://github.com/jaisurya143/NearMe/assets/121999338/fddfa61c-394a-452a-bc52-a7ba97b74b81)
![image](https://github.com/jaisurya143/NearMe/assets/121999338/41062312-b371-4e5d-b2cf-7a304c2daf05)
![image](https://github.com/jaisurya143/NearMe/assets/121999338/c0832e58-138c-4507-89b3-650497747a9b)
![image](https://github.com/jaisurya143/NearMe/assets/121999338/95b2b802-3a86-4c2a-a23a-b6f42a7241c9)









## RESULT
The program for implementing image maps using HTML is executed successfully.
