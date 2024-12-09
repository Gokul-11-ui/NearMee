# Ex04 Places Around Me
## Date: 9/12/2024

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

## CODE```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-09 230651.png" width="1520" height="750" usemap="#mymap">
    <map name="mymap">
        <area shape="rect" coords="1108,211,1320,356" title="suseela chockalingam mahaal" href=file:///C:/Users/admin/NearMe/img/imgapp/static/imap1.html>
        <area shape="rect" coords="1137,539,953,383" title="rajeshwari theatre" href=file:///C:/Users/admin/NearMe/img/imgapp/static/imap2.html>
        <area shape="rect" coords="386,486,654,659" title="Book store" href=file:///C:/Users/admin/NearMe/img/imgapp/static/imap3.html>
        <area shape="rect" coords="303,638,461,780" title="union bank" href=file:///C:/Users/admin/NearMe/img/imgapp/static/imap4.html>
        <area shape="rect" coords="768,35,916,169" title="sun shine school" href=file:///C:/Users/admin/NearMe/img/imgapp/static/imap5.html>
</html>
imap 1                                                                                                                                                                     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohan Electric Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to SUSEELA CHOCKALINGAM MAHAAL</h1>
    <p>START A NEW LIFE </p>
</header>



<div class="container">
    <h2>Our FACILIIES</h2>

    <div class="product">
        <p>WE ARE PROVIDING CATERING SERVICES AND AC/NON AC ROOMS </p>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Electric Avenue,ARANI</p>
    <p><strong>Phone:</strong>9874563210</p>
    <p><strong>Email:</strong> contact@SUSEELA@gmail.com</p>
</div>

<footer>
    <p>&copy; 2024 suseela mahaal. All rights reserved.</p>
</footer>

</body>
</html>
imap 2                                                                                                                                                                        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medical Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            margin-top: 20px;
            padding: 10px;
            background-color: #e8f5e9;
            border-left: 5px solid #4caf50;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4caf50;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>SRI RAJESHWARI THEATRE </h1>
    </header>
    <main>
        <h2>About Us</h2>
        <p>Welcome to rajeshwari theatre, WE HAVE THREE SCREENS AND PREMIUM SEATS COUPLE SEATS AND BIG SCREEN WITH SNACKS </p>
        <ul>
            <li>Friendly and knowledgeable staff</li>
            <li>Convenient delivery services</li>
            <li>24/7 customer support for emergencies</li>
        </ul>
        <div class="contact">
            <h3>Contact Us</h3>
            <p><strong>Address:</strong> Wellness Street,ARANI</p>
            <p><strong>Phone:</strong>9632014587</p>
            <p><strong>Email:</strong> rajeshwari@gmail.com</p>
            <p><strong>Opening Hours:</strong> Mon-Sun: 8:00 AM - 10:00 PM</p>
        </div>
    </main>
    <footer>
        &copy; 2024 sri rajeshwari theatre. All Rights Reserved.
    </footer>
</body>
</html>
imap 3                                                                                                                                                                        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f3e9;
            color: #333;
        }
        header {
            background-color: #6c5ce7;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            margin-top: 20px;
            padding: 10px;
            background-color: #e3d9fc;
            border-left: 5px solid #6c5ce7;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #6c5ce7;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Aruna Book Store</h1>
    </header>
    <main>
        <h2>Welcome to Aruna Book Store</h2>
        <p>Your one-stop destination for a wide range of books! At Book Haven, we believe in the power of stories to inspire, educate, and entertain. Whether you’re a fan of fiction, non-fiction, academic textbooks, or rare collectibles, we have something for everyone.</p>
        <h3>Why Shop With Us?</h3>
        <ul>
            <li>A vast collection of books across all genres</li>
            <li>Affordable prices and great deals</li>
            <li>Friendly staff to assist you in finding the perfect read</li>
            <li>Book clubs and author meet-ups</li>
        </ul>
        <div class="contact">
            <h3>Contact Us</h3>
            <p><strong>Address:</strong> Literary Lane,arani</p>
            <p><strong>Phone:</strong>9510236547</p>
            <p><strong>Email:</strong> info@arunabookstore.com</p>
            <p><strong>Opening Hours:</strong> Mon-Sat: 9:00 AM - 8:00 PM, Sun: 10:00 AM - 6:00 PM</p>
        </div>
    </main>
    <footer>
        &copy; 2024 Aruna Book Store. All Rights Reserved.
    </footer>
</body>
</html>
imap 4                                                                                                                                                              <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UNION BANK OF INDIA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Union Bank Of India</h1>
    <p>your money our responsible</p>
</header>

<div class="container">
    <h2>about us</h2>

    <div class="product">
        <p>Union Bank of India is one of the leading public sector banks of the country. The Bank is a listed entity, and the Government of India holds 74.76 percent in Bank’s total paid-up capital. The Bank, having its headquarters at Mumbai (India), was registered on November 11, 1919 as a limited company. On 1st April 2020, Andhra Bank and Corporation Bank were amalgamated into Union Bank of India. </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> City union bank,Ramnadu</p>
    <p><strong>Phone:</strong>9874563210</p>
    <p><strong>Email:</strong> cityunionbank.com</p>
</div>



</body>
</html>                                                                                                                                                                          
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sun shine kid school</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to sun shines kid school</h1>
    <p>education is the key of success</p>
</header>

<div class="container">
    <h2>about us</h2>

    <div class="product">
        <p>Our dedicated Teachers and staff are here to guide and support our students to explore new ideas, and challenges and to develop critical thinking skills. We believe in a culture of inclusivity, respect,At Sunshine Chennai Senior Secondary School your child will enter the world of Letters to take great strides towards success in lifeSun Shine Kids School located in Ramanathapuram, Krishnagiri. Find details for fee structure, reviews, admission process 2022-23. Easily compare for grade Play - Nursery on Skoodos
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> sun shines kid school,Ramnadu</p>
    <p><strong>Phone:</strong>9874563210</p>
    <p><strong>Email:</strong> sunshine@gmail.com</p>
</div>



</body>
</html>


## OUTPUT

![alt text](<Screenshot 2024-12-09 230651.png>)
![alt text](<Screenshot 2024-12-09 232636.png>)
![alt text](<Screenshot 2024-12-09 232831.png>)
![alt text](<Screenshot 2024-12-09 233228.png>)
![alt text](<Screenshot 2024-12-09 233835.png>)
![alt text](<Screenshot 2024-12-09 234431.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
