# Ex04 Places Around Me
## Date: 

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
<html>
    <head>
        {% load static %}
        <title>Map</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Saravanampatti</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Kanmani U(212221040070)</b></font>
        </h3>
        <center>
            <img src="{% static 'images/map.png' %}"  usemap="#Mycity" height="610" width="1450">
            <map name="Mycity">
<map name="image-map">
    <area target="" alt="Ragava Garden" title="Ragava Garden" href="garden.html" coords="1267,562,1411,625" shape="rect">
    <area target="" alt="KSIRS School" title="KSIRS School" href="ksirs.html" coords="78,833,108" shape="circle">
    <area target="" alt="AKR Express Parcel Service" title="AKR Express Parcel Service" href="akr.html" coords="1682,562,1845,610" shape="rect">
    <area target="" alt="Arokiya Food Industry" title="Arokiya Food Industry" href="arokiya.html" coords="1240,840,1403,898" shape="rect">
    <area target="" alt="Super Gym" title="Super Gym" href="gym.html" coords="1769,949,48" shape="circle">
</map>
        </center>  
    </body>
</html>
```


## OUTPUT

![image](https://github.com/kanmanikannu/NearMe/assets/114866367/53e3e1c0-e291-418a-b445-9227657181ab)

![Screenshot 2024-05-06 222718](https://github.com/kanmanikannu/NearMe/assets/114866367/21d675c2-c3cd-403f-aa15-3957d61da9ed)

![Screenshot 2024-05-06 222747](https://github.com/kanmanikannu/NearMe/assets/114866367/fad60d44-884d-4836-8f2f-709482535864)

![Screenshot 2024-05-06 222824](https://github.com/kanmanikannu/NearMe/assets/114866367/4e26ba21-77fd-4028-a0d7-f100843fef4c)

![Screenshot 2024-05-06 222844](https://github.com/kanmanikannu/NearMe/assets/114866367/3553776b-6c7e-413e-8614-da82a468b104)

![Screenshot 2024-05-06 222933](https://github.com/kanmanikannu/NearMe/assets/114866367/ea6507c1-3265-45d3-a489-01c87889fb17)


## RESULT
The program for implementing image maps using HTML is executed successfully.
