# Ex04 Places Around Me
# Date:15.10.2024
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
image map
```
<!DOCTYPE html>
<html>
<head>
    <title>Image Map</title>
</head>
<body>

<h1>Image Map</h1>
<img src="C:\Users\admin\Desktop\html1\mapimages.png" alt="map" style="max-width: 100%; height: auto;" usemap="#shop-map">

<map name="shop-map">
    <!-- Mathew Garments -->  
    <area shape="rect" coords="950,488,1200,542" href="file:///C:/Users/admin/Desktop/html1/image%20mapping/website%201.html" alt="Mathew Garments">

    <!-- Shanti Jewelry -->
    <area shape="rect" coords="589,335,815,438" href="file:///C:/Users/admin/Desktop/html1/image%20mapping/websitte%202.html" alt="Shanti Jewelry">

    <!-- Aswin's Snacks and Sweets -->
    <area shape="rect" coords="144,363,433,419" href="website 4.html" alt="Aswin's Snacks and Sweets">

    <!-- Naiduhall -->
    <area shape="rect" coords="255,290,421,422" href="website5.html" alt="Naiduhall">
    
    <!-- Jockey -->
    <area shape="rect" coords="898,597,1147,662" href="website 3.html" alt="Jockey">
</map>

</body>
</html>
```
website 1
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Mathew Garments</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #2a4d39; 
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #2a4d39; 
        }

        footer {
            background-color: #2a4d39; 
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>About Mathew Garments</h1>
    </header>
    <img src="mg.jpg" alt="Mathew Garments Logo" style="width: 300px; height: auto; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">


    <main>
        <section class="section">
            <h3>Introduction</h3>
            <p>Matthew Garments is a leading fashion brand known for its stylish and high-quality clothing. Established with the goal of offering sophisticated, comfortable, and versatile apparel, Matthew Garments has become a favorite among fashion-forward individuals globally.</p>
    
        </section>

        <section class="section">
            <h3>History</h3>
            <p>Founded by Matthew Johnson, the company started as a small tailoring business. Over the years, it expanded into a full-fledged brand offering a wide range of ready-to-wear clothing. Today, Matthew Garments is recognized for its timeless designs and commitment to quality craftsmanship.</p>
        </section>

        <section class="section">
            <h3>Products</h3>
            <p>Matthew Garments offers an extensive collection of stylish apparel for both men and women, including:</p>
            <ul>
                <li>Tailored Suits and Blazers</li>
                <li>Causal Shirts and T-Shirts</li>
                <li>Trendy Jeans and Pants</li>
                <li>Coats, Jackets,Hats, Scarves, Belts</li>
            </ul>
        </section>

    </main>

    <footer>
        <p>2024 Matthew Garments. All rights reserved.</p>
    </footer>

</body>
</html>

```
website 2
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Shanti Jewelry</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color:rgb(238, 213, 69);
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color:rgb(238, 213, 69)
        }

        footer {
            background-color:rgb(238, 213, 69);
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Shanti Jewelry</h1>
    </header>
    <img src="sj.jpg" alt="Shanti Jewellers logo" style="width: 300px; height: auto; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">

    <main>
        <div class="section">
            <h2>About Us</h2>
            <p>One of South Chennai’s most leading Jewellers specializing in latest designs of contemporary traditional and fashionable ornaments made in Gold, Silver, in plain and stone studded Jewellery with diamonds, rubies emerald and other precious stones. One of the biggest and the largest Jewellery in Kancheepuram District and with the wide range of display of exquisite Jewellery collection on an area of 3000 sq.ft.</p>
        </div>

        <div class="section">
            <h2>Our Services</h2>
            <p>For wedding occasion or light weight wear for career women or ranges for men’s wear anything and everything under one roof. Renowned for commitment of quality and service with over 110 years of business standing in the same place has made them the household name in and around Pallavaram, Chennai.</p>
        </div>

        <div class="section">
            <h2>Contact Information</h2>
            <p>Visit us at: poonamalle,Pallavaram,in and around chennai. Call us at:97890-97890.</p>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Shanti Jewelry</p>
    </footer>
</body>
</html>
```
website 3
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Jockey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6f61; 
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #ff6f61; 
        }

        footer {
            background-color: #ff6f61; 
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        a {
            color: #ff6f61;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>About Jockey</h1>
    </header>
    <img src="j.jpg" alt="jockey logo" style="width: 300px; height: auto; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
    <main>
    
        <section class="section">
            <h2>History</h2>
          <p> Jockey International, Inc. is an American manufacturer of underwear, sleepwear, and activewear. Founded in 1876, the company is known for its high-quality products that prioritize comfort and style. With a long history of producing innovative undergarments, Jockey continues to be a household name in the apparel industry.</p>
            <p>Jockey was founded by Samuel T. Cooper in 1876 in the United States. The brand's signature moment came with the invention of the "Jockey Shorts" in the 1930s, which revolutionized the underwear industry. Over the decades, Jockey has expanded its product lines to include a variety of apparel for both men and women.</p>
        </section>

        <section class="section">
            <h2>Innovation and Comfort</h2>
            <p>Jockey is known for its commitment to innovation, using advanced fabric technologies to enhance comfort and performance. The brand continually introduces new materials, such as moisture-wicking and stretch fabrics, to keep up with the changing needs of its customers.</p>
        </section>

        <section class="section">
            <h2>Product Range</h2>
            <p>Jockey offers a wide range of clothing, including:</p>
            <ul>
                <li>Underwear (Boxers, Briefs, Boxer Briefs)</li>
                <li>Sleepwear</li>
                <li>Activewear</li>
            </ul>
        </section>


    </main>

    <footer>
        <p> 2024 Jockey International. All rights reserved.</p>
    </footer>

</body>
</html>
```
website 4
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Aswin's Snacks and Sweets</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color:  #ee3a3a; 
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #ee3a3a; 
        }

        footer {
            background-color: #ee3a3a; 
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Aswin's Snacks and Sweets</h1>
    </header>
    <img src="aswins.jpeg" alt="aswins Logo" style="width: 300px; height: auto; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">

    <main>
        <div class="section">
            <h2>About Us</h2>
            <p>Every bite is a celebration of our ethnic Indian flavours and rich heritage at Aswins Sweets. Made with traditionally followed and loved recipes that recite the epic stories of Indian flavours, at Aswins Sweets, we make our delicious delights with love.

                We bring home a reason to celebrate! A story that began in 2004 is now a beloved and trusted name in homes across Tamil Nadu, with 25 outlets and counting. We’ve proven ourselves to be a harbinger of pride and have withstood the test of time amidst the other brands, and we've secured a sweet spot in people's hearts with our Indian snacks and savouries. Using our whimsically inventive ideas and constant effort to manufacture different varieties of bites, our founder, K.R.V. Ganesan, has taken this organisation to new heights</p>
        </div>

        <div class="section">
            <h2>Our Menu</h2>
            <p>Our menu includes a wide range of items like Murukku, Sundal, Kuzhi Paniyaram, Vadai, Banana Chips, Adai, Pesarattu, Jalebi, Kalaadi, Payasam, Laddu, Mysore Pak, Arisi Thengai Payasam, Sarkarai Pongal, Coconut Burfi from crispy snacks to mouth-watering sweets. We also offer custom snack orders for events and celebrations.</p>
        </div>

        <div class="section">
            <h2>Contact Information</h2>
            <p>we have all over india delivery,and exciting offers Call us at: 98654-32130.</p>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Aswin's Snacks and Sweets</p>
    </footer>
</body>
</html>
```
website 5
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Naiduhall</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #6450fb; 
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #065e84; 
        }

        footer {
            background-color:#6450fb;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Naiduhall</h1>
    </header>
    <img src="n.jpg" alt="Naiduhall Logo" style="width: 300px; height: auto; display: block; margin: 20px auto; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
    <main>
        <div class="section">
            <h2>About Us</h2>
            <p>Stylish Dresses is a boutique offering a wide range of fashionable dresses for every occasion. Whether you're looking for a chic evening gown, a casual summer dress, or a statement piece for a special event, we have something for you.</p>
            <p>Our mission is to provide high-quality, fashionable clothing that empowers you to feel confident and stylish. We carefully select each piece to ensure it meets our standards of elegance and comfort.</p>
            <p>At Stylish Dresses, we believe in making every woman feel special, with outfits that are both timeless and on-trend. Our team is dedicated to offering personalized service to help you find the perfect dress.</p>
        </div>

        <div class="section">
            <h2>Our Collections</h2>
            <p>Our collection includes a variety of dresses, including elegant evening gowns, stylish cocktail dresses, and trendy casual wear. We focus on high-quality fabrics and timeless designs to ensure you feel confident and comfortable.</p>
            <p>Each collection is curated with the latest trends in mind, offering a blend of classic styles and modern designs. From bold prints to delicate lace, we have something to suit every taste.</p>
        </div>

        <div class="section">
            <h2>Contact Information</h2>
            <p>Visit us at tnagar Chennai Call us at:97687-65480. Follow us on social media for the latest collections and exclusive offers!</p>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Stylish Dresses</p>
    </footer>
</body>
</html>

```
# OUTPUT
![Screenshot 2024-12-07 001046](https://github.com/user-attachments/assets/a0ed0bfc-dc8a-448c-88a4-5826d826e8da)
![Screenshot 2024-12-07 001242](https://github.com/user-attachments/assets/7f342c53-f84d-47b5-9a9c-99209a47b18f)
![Screenshot 2024-12-07 001321](https://github.com/user-attachments/assets/673d3050-4cfb-4c43-9fea-d7c68d6d43bb)
![Screenshot 2024-12-07 001356](https://github.com/user-attachments/assets/2a97b1fb-00a8-4c42-b6e2-207ae59f41dd)
![Screenshot 2024-12-07 001446](https://github.com/user-attachments/assets/1840b525-538a-46a7-a9da-a6270ecd34b1)
![Screenshot 2024-12-07 001538](https://github.com/user-attachments/assets/37c0e68a-70be-40ac-8bd6-462e766c1513)






# RESULT
The program for implementing image maps using HTML is executed successfully.
