# Ex04 Places Around Me
## Date: 26.04.2025

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
map.html
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SHIVASRI (212224220098)</b></font>
</h3>
<center>
<img src="chennai.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="100,100,900,500" href="home.html" title="My home town">
<area shape="rect" coords="700,100,900,400" href="vr.html" title="vr mall">
<area shape="rect" coords="570,100,900,45" href="marina.html" title="marina beach">
<area shape="rect" coords="640,100,900,140" href="mahabalipuram.html" title="mahabalipuram">
<area shape="rect" coords="950,100,900,550" href="mgm.html" title="MGM">
</map>
</center>
</body>
</html>
```
vr.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VR MALL</title>
    <style>
        h1 {
            color: red;
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: blue;
        }

        body {
            background-color: yellow;
        }
    </style>
</head>

<body>
    <h1>VR mall</h1>
    <hr color="black">
    <p><b>
        VR Mall Chennai, located in the upscale neighborhood of Anna Nagar, is one of the city's most prominent and contemporary lifestyle destinations. Spanning over 1.8 million square feet, the mall is known for its modern architecture, open spaces, and a thoughtfully curated mix of retail, dining, and entertainment. It houses a wide range of national and international brands, offering fashion, electronics, lifestyle, and home décor, catering to diverse shopping preferences.

        The mall features a state-of-the-art PVR Cinemas multiplex, a vibrant food court, and several fine-dining restaurants serving global cuisines. It frequently hosts art exhibitions, music performances, and cultural festivals, making it not just a shopping destination but a cultural and social hub. VR Chennai is also notable for integrating sustainability and local culture into its design, with murals, sculptures, and art installations that reflect the spirit of Chennai.
        
        With ample parking, accessibility features, and a family-friendly environment, VR Mall Chennai offers a complete urban experience. Whether you're looking to shop, dine, watch a movie, or simply unwind, the mall provides a stylish and engaging atmosphere for locals and tourists alike.
        
        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>
```
marina.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marina beach</title>
    <style>
        h1 {
            color: brown;
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(227, 83, 83);
        }


        body {
            background-color: rgb(171, 147, 215);
        }
    </style>
</head>

<body>
    <h1>Marina beach</h1>
    <hr color="black">
    <p><b>Marina Beach, located in Chennai along the Bay of Bengal, is the longest beach in India and one of the longest urban beaches in the world, stretching over 13 kilometers. It is a key landmark of the city and a favorite spot for locals and tourists alike. Known for its golden sands and breezy shoreline, the beach is most lively during early mornings and evenings, offering beautiful sunrise views and a relaxing atmosphere.

        Visitors can enjoy traditional street snacks like sundal and murukku, take horse or pony rides, and fly kites along the wide promenade. The beach is also home to several statues and memorials, including tributes to Mahatma Gandhi, Tamil scholars, and former chief ministers like M.G. Ramachandran and C.N. Annadurai. It serves not only as a place of leisure but also as a cultural and political gathering point.
        
        Though swimming is not recommended due to strong currents, Marina Beach remains a symbol of Chennai’s heritage. With nearby attractions like the lighthouse, aquarium, and historic buildings, it offers a rich blend of history, culture, and recreation.
        
    <br><br>
    <hr color="black">
</body>

</html>

```
mahabalipuram.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahabalipuram</title>
    <style>
        h1 {
            color: rgb(210, 56, 221);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(41, 41, 238);
        }

        body {
            background-color: rgb(80, 235, 109);
        }
    </style>
</head>

<body>
    <h1>Mahabalipuram</h1>
    <hr color="black">
    <p><b>Mahabalipuram, also known as Mamallapuram, is a historic coastal town located about 60 kilometers south of Chennai in Tamil Nadu. Renowned for its ancient rock-cut temples and monuments, it is a UNESCO World Heritage Site that showcases the architectural brilliance of the Pallava dynasty, which ruled during the 7th and 8th centuries. The town is famous for its shore temple, Pancha Rathas (Five Chariots), Arjuna’s Penance, and various cave sanctuaries, all carved from granite.

        Set against the scenic backdrop of the Bay of Bengal, Mahabalipuram attracts tourists, historians, and art enthusiasts from around the world. Its temples and sculptures reflect a fusion of religious themes and mythical stories, making it an open-air museum of ancient Indian art and architecture. The town is also known for its stone-carving traditions, which continue to thrive today.
        
        In addition to its historical significance, Mahabalipuram is a popular beach destination, ideal for relaxing, surfing, and enjoying seafood. Cultural festivals, including traditional dance performances, are regularly held near the monuments. With its blend of history, culture, and coastal charm, Mahabalipuram offers a unique and enriching experience.
        
        
    <hr color="black">
</body>

</html>
```
mgm.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MGM</title>
    <style>
        h1 {
            color: rgb(48, 234, 221);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(59, 52, 104);
        }

        body {
            background-color: rgb(249, 42, 242);
        }
    </style>
</head>

<body>
    <h1>MGM</h1>
    <hr color="black">

    <p><b>MGM Dizzee World is one of the most popular amusement parks in Chennai, located on the East Coast Road (ECR) near Muttukadu. Established in the early 1990s, it has been a favorite destination for families, school trips, and thrill-seekers for decades. Spanning a large area, the park offers a variety of attractions, including water rides, roller coasters, and themed zones that cater to visitors of all age groups.

        Some of the highlights include the Big Wheel, Spider Spin, Wave Pool, and the Rainbow River. There’s also a dedicated kids’ zone with gentle rides and play areas. MGM Dizzee World blends fun with safety, maintaining high standards of cleanliness and security. The park also features live entertainment shows, food courts, and shaded rest areas to enhance the visitor experience.
        
        Its location along the scenic ECR adds to the charm, making it a great stop during road trips. With a mix of adrenaline-pumping rides and relaxing zones, MGM Dizzee World offers a perfect day out for both fun and relaxation.
        
        
        
    <br><br>
    <hr color="black">
</body>

</html>

```

## OUTPUT

![Screenshot 2025-04-29 134833](https://github.com/user-attachments/assets/3e6df41b-6bae-4006-b0b0-e10132087e63)
![Screenshot 2025-04-29 133929](https://github.com/user-attachments/assets/0ac73876-5136-4e96-9ed5-4dc6ea9f9e5e)

![Screenshot 2025-04-29 133848](https://github.com/user-attachments/assets/2fbf00d4-b623-4036-a699-8f83cec7cb5f)

![Screenshot 2025-04-29 133838](https://github.com/user-attachments/assets/3bb73667-dfde-477e-a3b4-d783af84ed7d)

![Screenshot 2025-04-29 133858](https://github.com/user-attachments/assets/3942e71a-9984-4e1a-b50b-8a359e86186b)








## RESULT
The program for implementing image maps using HTML is executed successfully.
