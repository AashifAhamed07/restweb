# Ex.07 Restaurant Website
## Date:08.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FUEGO Restaurant</title>
  <link rel="stylesheet" href="stylex.css">
</head>
<body>
  <header>
    <img src="em.jpeg" alt="Logo">
    <h1>FUEGO RESTAURANT</h1>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Admin</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <div class="content">
    <h2 align="center">AASHIF AHAMED S-(25013503)</h2>
    <h2>“Where every bite ignites a spark of flavor.”</h2>
    <h2>“Savor the fire. Taste the passion.”</h2>
    <p>Welcome to FUEGO — where fine taste meets fiery creativity.</p>
    <p>Experience the best dining ambiance with hand-crafted dishes and passion-filled service.</p>
    <img class="restaurant-img" src="re.jpeg" alt="Restaurant Interior">
    <h6 align="border-bottom">&copy; Designed and Developed by Aashif Ahamed S</h6>
  </div>
</body>
</html>

stylex.css

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #ff6600;
    }
    header img {
      width: 60px;
      vertical-align: middle;
      border-radius: 50%;
    }
    header h1 {
      display: inline;
      font-size: 2.5rem;
      color: #ff6600;
      margin-left: 10px;
    }
    nav {
      text-align: center;
      background-color: #1a1a1a;
      padding: 10px;
    }
    nav a {
      text-decoration: none;
      color: white;
      padding: 14px 20px;
      display: inline-block;
      transition: 0.3s;
    }
    nav a:hover {
      background-color: #ff6600;
      border-radius: 5px;
    }
    .content {
      text-align: center;
      padding: 40px;
    }
    .content h2 {
      font-weight: bold;
      color: #ff6600;
    }
    .content p {
      font-size: 1.2rem;
      margin: 10px 0;
    }
    .restaurant-img {
      width: 80%;
      border-radius: 15px;
      margin-top: 20px;
      box-shadow: 0 0 20px #ff6600;
    }
    .menu-section {
      text-align: center;
      margin: 40px;
    }
    .item {
      margin: 15px;
    }
    .item img {
      width: 200px;
      border-radius: 10px;
      margin: 10px;
      box-shadow: 0 0 15px #ff6600;
    }
    .h1 {
      color: #ff6600;
      margin-top: 20px;
    }
    .admin {
      display: inline-block;
      margin: 30px;
    }
    .admin img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      box-shadow: 0 0 15px #ff6600;
    }
    .admin .role {
      font-weight: bold;
      margin-top: 10px;
    }
    .contact-box {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 40px;
      border-radius: 15px;
      text-align: center;
      width: 50%;
      margin: 100px auto;
      box-shadow: 0 0 20px #ff6600;
    }
    .contact-box h1 {
      color: #ff6600;
    }

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - FUEGO</title>
  <link rel="stylesheet" href="stylex.css">
</head>
<body>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Admin</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <h1 style="text-align:center; color:#ff6600;">Our Menu</h1>

  <div class="menu-section">
    <h2>Biriyani</h2>
    <div class="item">Chicken Biriyani — ₹120 <br><img src="cb.jpeg" alt="Chicken Biriyani"></div>
    <div class="item">Mutton Biriyani — ₹190 <br><img src="mb.jpeg" alt="Mutton Biriyani"></div>
    <div class="item">Veg Biriyani — ₹70 <br><img src="vb.jpeg" alt="Veg Biriyani"></div>

    <h2>Fast Food</h2>
    <div class="item">Chicken Fried Rice — ₹100 <br><img src="cr.jpeg" alt="Chicken Fried Rice"></div>
    <div class="item">Veg Fried Rice — ₹70 <br><img src="vr.jpeg" alt="Veg Fried Rice"></div>
    <div class="item">Chicken Fried Noodles — ₹100 <br><img src="cn.jpeg" alt="Chicken Fried Noodles"></div>

    <h2>Juice</h2>
    <div class="item">Lemon Juice — ₹40 <br><img src="lj.jpeg" alt="Lemon Juice"></div>
    <div class="item">Chocolate Milkshake — ₹55 <br><img src="cm.jpeg" alt="Chocolate Milkshake"></div>

    <h2>Ice Cream</h2>
    <div class="item">Chocolate Ice Cream — ₹90 <br><img src="ci.jpeg" alt="Chocolate Ice Cream"></div>
    <div class="item">Strawberry Ice Cream — ₹100 <br><img src="si.jpeg" alt="Strawberry Ice Cream"></div>
  </div>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin - FUEGO</title>
  <link rel="stylesheet" href="stylex.css">
</head>
<body>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Admin</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <h1 style="text-align:center; color:#ff6600;">Our Team</h1>

  <div class="admin">
    <img src="founder.jpeg" alt="Founder">
    <div class="role">FOUNDER</div>
    <div>AASHIF AHAMED S</div>
  </div>

  <div class="admin">
    <img src="Chairman.jpg" alt="Chairman">
    <div class="role">CHAIRMAN</div>
    <div>VIVEK CHRISTO</div>
  </div>

  <div class="admin">
    <img src="Manager.jpg" alt="Manager">
    <div class="role">MANAGER</div>
    <div>SURYA PRAKASH</div>
  </div>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - FUEGO</title>
  <link rel="stylesheet" href="stylex.css">
</head>
<body>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Admin</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <div class="contact-box">
    <h1>Contact Us</h1>
    <p><strong>Phone:</strong> 9554495544</p>
    <p><strong>Address:</strong> No.210/A, Flame Street, Chennai, India</p>
  </div>
</body>
</html>


```


## OUTPUT:

![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32)-1.png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
