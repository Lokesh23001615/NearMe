# Ex04 Places Around Me
## Date: 22.03.2024

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
<title>Places Nearby me</title>
</head>

<body align="center">
<h1 align="center">
<font color="skyblue">Virudhachallam</font>
</h1>
<h2 align="center">
<font color="magenta">LOKESH M (212223230114) </font>
                        
</h2>
<img src="places.png" usemap="#image-map">

<map name="image-map">
<area target="" alt="Poorvika Mobiles" title="Poorvika Mobiles" href="mobile.html" coords="684,292,835,342" shape="rect">
<area target="" alt="Sri Annapoorani" title="Sri Annapoorani" href="hotel.html" coords="1311,782,93" shape="circle">
<area target="" alt="Jai Sai Krishna" title="Jai Sai Krishna" href="cinema.html" coords="569,70,76" shape="circle">
<area target="" alt="Siva Pooja Marriage Hall" title="Siva Pooja Marriage Hall" href="marriagehall.html" coords="797,826,52" shape="circle">
<area target="" alt="Virudhagirishvarar Temple" title="Virudhagirishvarar Temple" href="temple.html" coords="576,536,382,481" shape="rect">
</map>
                        
               
</html>


temple.html

<html>
<head>
<title>Temple</title>
</head>
<body bgcolor="orange">
<h1 align="center"> 
<font color="red"><b>Virudhachallam</b></font>
=</h1>
<h3 align="center">
<font color="voilet"><b>Virudhagirishvarar Temple</b></font>
</h3>
<hr size="3" color="skyblue">
<p align="justify">
</html>
\<font face="Georgia" size="5">
                            
The Virudhagiriswarar Temple is a Hindu temple in the town of Virudhachalam, Cuddalore district of Tamil Nadu, India. 
The presiding deity Virudhagiriswarar is revered in Tevaram, written by Tamil saint poets known as the nayanmars and classified as Paadal Petra Sthalam. 
The temple gives its name to the town of Virudhachalam. 
The temple is famed for the legend of Shiva forming as a mountain heeding to the prayers of Brahma.

Virudhagirswarar temple is a part of the series of temples built by Sembiyan Mahadevi, the Chola queen along the banks of river Kaveri. 
It has several inscriptions dating back to the Chola period. The temple has six daily rituals at various times from 5:30 a.m. to 8 p.m., 
and three yearly festivals on its calendar. 
The annual Brahmotsavam (prime festival), Masi Magam, is attended by thousands of devotees from far and near. 
\The temple is maintained and administered by the Hindu Religious and Endowment Board of the Government of Tamil Nadu.
</font>
</p>
</body>
</html>

marriagehall.html

<html>
<head>
<title>Marriage Hall</title>
</head>
<body bgcolor="green">
<h1 align="center"> 
<font color="red"><b>Virudhachallam</b></font>
</h1>
<h3 align="center">
<font color="voilet"><b>Siva Pooja Marriage Hall</b></font>
</h3>
<hr size="3" color="skyblue">
<p align="justify">
</html>
<font face="Georgia" size="5">

Siva Pooja Marriage Hall is a renowned venue located in Virudhachallam. 
Known for its elegant ambiance and spacious halls, it offers a perfect setting for weddings and other special occasions. 
The hall is equipped with modern amenities and can accommodate large gatherings comfortably. 
With professional staff and excellent catering services, Siva Pooja Marriage Hall ensures a seamless and memorable event experience for guests. 
Its strategic location and ample parking facilities make it a preferred choice among those planning their celebrations.
</font>
</p>
</body>
</html>


cinema.html

<html>
<head>
<title>Cinema</title>
            </head>
<body bgcolor="cyan">
<h1 align="center"> 
<font color="red"><b>Virudhachallam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Jai Sai Krishna Cinemas A/C</b></font>
</h3>
<hr size="3" color="yellow">
<p align="justify">
</html>
<font face="Georgia" size="5">
                            
Jai Sai Cinemas A/C is a popular movie theater located in Virudhachallam. 
Renowned for its comfortable and air-conditioned auditoriums, it provides a delightful movie-watching experience for audiences. 
The cinema boasts state-of-the-art sound systems and high-quality projection technology, ensuring top-notch visual and audio quality for all screenings.
With multiple screens, Jai Sai Cinemas A/C offers a diverse selection of films catering to various tastes and preferences. 
Its convenient location and ample parking make it a favorite destination for moviegoers in the area. 
The cinema also offers affordable ticket prices and special deals, making it accessible to a wide range of audiences. 
Along with its friendly staff and clean facilities, Jai Sai Cinemas A/C strives to provide an enjoyable and memorable cinematic experience for all patrons.
</font>
</p>
</body>
</html>


hotel.html

<html>
<head>
<title>Hotel</title>
</head>
<body bgcolor="magenta">
<h1 align="center"> 
<font color="black"><b>Virudhachallam</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Sri Annapoorani</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
</html>
<font face="Georgia" size="5">

Sri Annapoorna Hotel is a well-established dining destination renowned for its delectable South Indian cuisine, located in Virudhachallam. 
Boasting a warm and inviting ambiance, it provides a comfortable setting for patrons to enjoy their meals. 
The restaurant offers a wide array of traditional dishes, ranging from crispy dosas and fluffy idlis to flavorful curries and aromatic biryanis. 
With its emphasis on quality ingredients and authentic flavors, Sri Annapoorna Hotel has earned a loyal following among locals and visitors alike. 
Its attentive staff and efficient service ensure a pleasant dining experience for all guests. 
Additionally, the restaurant provides catering services for events and special occasions, further extending its hospitality beyond its premises. 
Whether for a quick bite or a leisurely meal, Sri Annapoorna Hotel promises a taste of genuine South Indian culinary excellence.

</font>
</p>
</body>
</html>

mobile.html

<html>
<head>
<title>Mobile Shop</title>
</head>
<body bgcolor="grey">
<h1 align="center"> 
<font color="blue "><b>Virudhachallam</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Poorvika Mobiles</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
Poorvika is the Largest Tech Retailer in India, spanning across 460+ showrooms in and around Tamil Nadu, Karnataka, Pondicherry, Mumbai, Pune and Trivandrum, 
famous for their touch & feel experience.
Poorvika sells a wide category of devices in its showrooms and Online portal, ranging from the Best Smartphones, Laptops, Computers, Smart Devices, Smart TVs to Accessories. 
Poorvika's E-Commerce platform www.poorvika.com caters to customers across India where Customers can Comfortably Order their devices with just a tap and get them delivered 
Safely with delivery options such as 2 Hours Delivery, Same Day Delivery, Next Day Delivery, and a Pickup at the Store option based on their location. 
Having served over 5 Crore+ Happy Customers, Poorvika takes pride in being India's leading retailer for Top Brands like
Apple, Samsung, Oppo, Vivo, Xiaomi, OnePlus, Redmi, Realme, Nokia, etc.
</font>
</p>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-03-22 103733.png>)


![alt text](<Screenshot 2024-03-22 103856.png>)



![alt text](<Screenshot 2024-03-22 103913.png>)


![alt text](<Screenshot 2024-03-22 103715.png>)



![alt text](<Screenshot 2024-03-22 104005.png>)



![alt text](<Screenshot 2024-03-22 103839.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
