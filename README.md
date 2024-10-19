# Ex04 Places Around Me
## Date: 21-10-2024

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
Map.Html
```
<html>
    <head>
        <title>
            NELLORE
        </title>
    </head>
    <body>
        <h1 align="center">NELLORE(Viswanadham venkata sai sruthi)</h1>
        <center>
            <img src="imagemap.png" usemap="#mapnew">
            <map name="mapnew">
                <area target="" alt="MGB Mall" title="MGB_Mall" href="MGB.html" coords="616,99,775,142" shape="rect">
                <area target="" alt="KIMS Hospital" title="KIMS_Hospital" href="KIMS.html" coords="263,71,61" shape="circle">
                <area target="" alt="Mypadu Beach" title="Mypadu_Beach" href="Mypadu.html" coords="63,481,107,457,179,485,167,521,60,524" shape="poly">
                <area target="" alt="Penchalakona" title="Penchalakona" href="Penchalakona.html" coords="589,179,41" shape="circle">
                <area target="" alt="Hotel Minerva Grand" title="Hotel_Minerva_Grand" href="Minerva.html" coords="256,405,326,436,289,488,204,473,183,422" shape="poly">
            </map>
        </center>
    </body>
</html>
```

MGB.HTML
```
<html>
    <head>
        <title>
            MGB Mall
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">MGB_Mall</h1>
        <p>
            The MGB Mall is  located in nellore. This mall is one of the famous mall in andhra pradesh. Vibrant mall featuring retail shops, boutiques, fast-food outlets & other eateries, plus a theater.Nellore is one of the famous town.Many people come here to relax themselves.

            Best place to hangout with family and friends food and ambience also very nice. The mall was developed by the Nellore-based MGB Group, which has a 90-year history.  MGB Felicity Mall is located in Dargamitta, a prominent area of Nellore.  It has many national and international brands, including BigBazar, Reliance Footprint, Mc'donalds, KFC, Satyam, and Dominos. It's one of the largest malls in Andhra Pradesh.  It has SPICE CINEMA with five 4k screens and Dolby sound, and a 12,000 sq. ft. gaming zone. 

        </p>
        <center>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTszEKr3fGfjDjq5A2h8SEciki3tkHtei3rHw&s" width="600" height="300">
        </center>
    </body>
</html>
```
beach.html
```
<html>
    <head>
        <title>
            Mypadu Beach
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: #de1212;
            }
            p{
                font-size: medium;
            }
            
        </style>
    </head>
    <body>
        <h1 align="center">Mypadu_Beach

        </h1>
        <p>
            Mypadu Beach is a pristine beach in the SPSR Nellore district of Andhra Pradesh that is maintained by the Andhra Pradesh Tourism Development Corporation (APTDC). The beach provides fishing opportunities for the local fishermen, and access to cruises for the tourists. The beach has golden brown sand and clear seawater. It's a great place for relaxing, sunbathing, and taking long walks. There's an old Shiva temple next to the beach that attracts many tourists and believers. 
            The Andhra Pradesh Tourism Development Corporation (APTDC), is taking certain measures to promote Mypadu Beach as a tourist destination by setting up recreational activities such as water sports and development of resorts. The natural beauty and soothing atmosphere of the place are some of the main factors that draw the attention of tourists.
        </p>
        <center>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Mypadu-beach_nellore.jpg/1024px-Mypadu-beach_nellore.jpg" 
        </center>
    </body>
</html>
```
penchalakona.html
```
<html>
    <head>
        <title>
            Penchalakona
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Penchalakona</h1>
        <p>
            Penchalakona is a village in the Rapur Mandal of Nellore district in Andhra Pradesh, India. It's known for the Penusila Lakshmi Narasimha Swamy temple, a Nava Narasimha temple, and the Penchalakona Waterfalls.A famous waterfall in Andhra Pradesh, located a few kilometers from the village center. It takes about half an hour to reach the falls from the temple.The Sri Raja Rajeswari Temple is located next to the Penchalakona Bustand. The Gonupalli Swamy Temple is located about 5 kilometers before Penchalakona. 
            Located at the base of the Penchalakona Valley, this temple features an image of the Lord as a self-manifested one (Swayambhu). The image is of two stones that form a lion's head on a man's body.
        </p>
        <center>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRm9-wPtEuD5d4LEbXUYO8k6XvrrAgmpMRHgA&s" width="600" height="300">
        </center>
    </body>
</html>
```
Minerva.Html
```
<html>
    <head>
        <title>
            Hotel Minerva Grand
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Hotel_Minerva_Grand</h1>
        <p>
            Minerva Group of Hotels and Restaurants. Being a boutique business hotels & restaurants chain, it strides on to break new grounds with its state-of-the-art conveniences, distinct services and fine dining familiarities.Our Dining
            Indulge in a culinary journey that delights the senses and captures the essence of BLUE FOX . Our expert chefs have meticulously crafted a menu that showcases the finest ingredients, innovative flavors, and exquisite presentations.It is located in Grand Trunk Road, Nellore - 0861 235 8888.It has 106 Elite Rooms & Suites catering to every class of traveler be it business or leisure from India & abroad. 
            The Lunch food quality was very good and the service in the Restaurant was very fast. The Breakfast was hot and tasty.Location is very good .
        </p>
        <center>
            <img src="https://minervahotels.in/wp-content/uploads/2023/10/nellore-grandtrunk-road.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/0644e39d-552f-4919-ba55-4adf78f727a2)
![image](https://github.com/user-attachments/assets/56eca6c3-4bc6-42e8-a13c-5f4db3d7512e)
![Screenshot 2024-10-20 000527](https://github.com/user-attachments/assets/e473f54b-ce7d-4d45-8870-ceef072f65ae)
![image](https://github.com/user-attachments/assets/18425006-6d83-4790-8365-436dd7ac3967)





## RESULT
The program for implementing image maps using HTML is executed successfully.
