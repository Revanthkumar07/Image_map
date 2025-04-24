# Ex04 Places Around Me
# Date:24-04-2025
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

# CODE:
```
map.html
 <html>
 <head>
 <title>MyCity</title>
 </head>
 <body>
<h1 align="center">
 <font color="black"><b>Nellore</b></font>
 </h1>
 <h3 align="center">
 <font color="blue">Beeda Venkata Revanth Kumar (212224240023)</font>
 </h3>
 <center>
  <img src="map.html.png" usemap="#MyCity"> 


    <map name="MyCity">
    <area target="" alt="pubg cafe" title="pubg cafe" href="cafe.html" coords="50,492,245,604" shape="rect">
    <area target="" alt="Amancharla forest" title="Amancharla forest" href="vadu.html" coords="503,212,719,309" shape="rect">
    <area target="" alt="poigai" title="poigai" href="poigai.html" coords="1104,585,1204,591" shape="rect">
    <area target="" alt="Temple" title="Temple" href="vellore.html" coords="886,403,1014,471" shape="rect">
    <area target="" alt="river" title="river" href="ba.html" coords="899,582,1010,640" shape="rect">
</map>
</center>
</body>
</html>


ba.html

<html>
    <body bgcolor="red">
        <font size="100">
            <li>river is a natural flowing watercourse, usually freshwater, flowing toward an ocean, sea, lake, or another river. Rivers are an essential component of the Earth's hydrological cycle, originating from sources such as springs, glaciers, or rainfall in high-altitude areas and traveling long distances before merging with larger water bodies.</li>
        </font>
    </body>
</html> 

vellore.html

<html>
    <body bgcolor="red">
        <font size="100">
            <li>The Golagamudi Venkaiah Swamy Temple, located approximately 12 km from Nellore in Andhra Pradesh, is a revered spiritual destination dedicated to Bhagavan Sri Venkaiah Swamy, a 20th-century saint regarded as an Avadhuta and an incarnation of Lord Dattatreya. Often referred to as the “Shirdi of the South,” the temple attracts devotees seeking spiritual solace and blessings.​</li>
        </font>
    </body>
</html> 

poigai.html

<html>
    <body bgcolor="red">
        <font size="100">
            <li>"coffee cafe is the good coffee to take cafe"</li>
            <li>"this is the best cafe and the cost is best"</li>
        </font>
    </body>
</html> 

vadu.html

<html>
    <body bgcolor="blue">
        <font size="100">
            <li>The Āmancharla East Reserved Forest is a protected forest area located in the Nellore district of Andhra Pradesh, India. Situated near the village of Siddavarapādu and close to Gotūruvārikhandrika, it lies approximately 9 km south of Jonnawada, a village in Buchireddypalem mandal. The forest is positioned at latitude 14.40447° N and longitude 79.87392° E, with an elevation of about 41 meters above sea level .​</li>
        </font>
    </body>
</html> 

```
# OUTPUT:
![alt text](<Screenshot 2025-04-24 182251.png>)
![alt text](<Screenshot 2025-04-24 183912.png>)
![alt text](<Screenshot 2025-04-24 183931.png>)
![alt text](<Screenshot 2025-04-24 184453.png>)
![alt text](<Screenshot 2025-04-24 184655.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
