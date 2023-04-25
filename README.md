# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new django project and app
### Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.

### Step 3: 
Type ur image map code in the html with coordinates and target file to redirect on click

### Step 4: 
Define your components pages and create content in such a way that it gives information about place which is being clicked

### Step 5: 
Include contents for your subpages and map them using urls and views

## Code:
#### index:
```python
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>


</h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            S KANTHA SISHANTH (212222100020)
        </font>
            
</h3>
        <center>
    
<img id="Image-Maps-Com-image-maps-2023-04-24-060015" src="Myhometown.jpg" border="0" width="1822" height="726" orgWidth="1822" orgHeight="726" usemap="#image-maps-2023-04-24-060015" alt="" />
<map name="image-maps-2023-04-24-060015" id="ImageMapsCom-image-maps-2023-04-24-060015">
<area  alt="" title="Fort" href="fort.html" shape="rect" coords="91,597,141,647" style="outline:none;" target="_self"     />
<area  alt="" title="Cineplex" href="cineplex.html" shape="rect" coords="1669,141,1719,191" style="outline:none;" target="_self"     />
<area  alt="" title="Marriage Hall" href="marriagehall.html" shape="rect" coords="1231,293,1281,343" style="outline:none;" target="_self"     />
<area  alt="" title="Hospital" href="hospital.html" shape="rect" coords="1298,367,1348,417" style="outline:none;" target="_self"     />
<area  alt="" title="Bus Stand" href="busstand.html" shape="rect" coords="1568,248,1618,298" style="outline:none;" target="_self"     />
<area shape="rect" coords="1820,724,1822,726" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>


</center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home town.<br>
                Click the location and get information about it.
            </font>
        </p>


</body>
</html>
```
#### Marriage Hall:
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        Marriage Hall
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        Valli Annamalai Thirumana Mahal
    </font>
</h1>
<p align="center">
    <font color="black" face="cursive" size="24 ">
         <br>Valli Annamalai Thirmana Maligai listed under Banquet Halls in Tiruvannamalai road, Gingee. Check Address, Contact Number, Ratings & Reviews,
Photos, Maps etc, on their official website.</br><br>Banquet Halls is an enclosed space suitable for hosting a variety of events such as birthday parties, corporate events, engagement ceremonies,weddings, receptions, etc. They are beautifully designed and decorated to create an elegant ambience for any event you are hosting. Banguet hal
can be booked for a stipulated time period during which the event has to take place.
        </br>

        </OL>


    </font>


</p>


</body>


</html>
```
#### Hospital:
```python


<!DOCTYPE html>
<html>
<head>
    <title>
        Hospital
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        E.K.R Multi Speciality Hospital
    </font>
</h1>
<p align="center">
    <font color="black" face="cursive" size="24 ">
         <br>E.K.R MULTI SPECIALITY HOSPITAL is one of the best Multi-Speciality hospital in Gingee founded by Dr. E. Anantha Murugan M.S., Initially started as a small clinic in 2018, the clinic has gained humongous trust from the public within a span of 1 year and got established itself as EKR Nursing home in 2019.</br>
         <br> Over the years it has been providing satisfactory and affordable health care solutions to the people of Gingee and its Suburbs.With increasing need for reliable healthcare it expanded into Multi Speciality Hospital. The hospital offers various services like consultation, treatments, procedures and surgery.
        </br>

        </OL>


    </font>


</p>


</body>


</html>
```
#### Bus Stand:
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        Bus Stand
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        Gingee Bus Stand
    </font>
</h1>
<p align="center">
    <font color="black" face="cursive" size="24 ">
         <br>It is a Small Bus Stand- Frequent buses available to Villupuram, Melmalaiyanur, Tiruvannamalai, Tindivanam, Vellore. Inter City and State Buses (Chennai, Pondicherry, Bangalore, Vellore) .</br>
         <br>All shops available nearby. Hotels & grocery shopping mall are very near. Greens and vegetables are available at low cost throughout the day. Flower & garland available at all the time. Upto 9.30pm buses available. Auto & other cabs also available. Mobile repair shops available. Recharge shops also available. Tea & snacks items available. Cool drinks and mineral water available. All News papers & magazines available at the earliest. Gooseberry & maize available.

        </br>

        </OL>


    </font>


</p>


</body>


</html>
```
#### Cineplex:
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        Cineplex
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        Saravana Cineplex
    </font>
</h1>
<p align="center">
    <font color="black" face="cursive" size="24 ">
         <br>One of the best theatre in Gingee, Theatre is clean with good ambiance. It is Well Maintained. Online booking facility available in ticketnew app. Parking and Food Court available here.</br><br>
        </br>

        </OL>


    </font>


</p>


</body>


</html>

```
#### Fort:
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        Fort
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
       Gingee Rajagiri Fort
    </font>
</h1>
<p align="center">
    <font color="black" face="cursive" size="24 ">
         <br>The Rajagiri Fort was built in 1200 AD. It is located in Rajagiri, Tamil Nadu, India, meaning Kings Hill. It is 1 km from Gingee Market. It is made up of saffron and black rock.
         Gingee Fort or Senji Fort (also known as Chenji, Chanchi, Jinji or Senchi) in Tamil Nadu, India is one of the surviving forts in Tamil Nadu, India.The site is so fortified that Shivaji, the Maratha king, ranked it as the "most impregnable fortress in India", and it was called the "Troy of the East" by the British.
        Originally built by Ananta Kon around 1190 AD and later fortified by Krishna Kon, it was later modified in the 13th century to elevate it to the status of an unbreachable citadel to protect the small town of saenji. It was also the headquarters domination in northern Tamil Nadu. 
        <br>

        </OL>


    </font>


</p>


</body>


</html>


```


## Output:
#### index:
![output](/images/index.png)
#### Marriage Hall:
![output](/images/marriagehall.png)
#### Hospital:
![output](/images/hospital.png)
#### Bus Stand:
![output](/images/busstand.png)
#### Cineplex:
![output](/images/cineplex.png)
#### Fort:
![output](/images/fort.png)
## Result:
Thus image mapping has been accomplished