# Ex.07 Restuarant Website
## Date:18.11.2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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

Restaurant.html

```
<html>
    
<head>
<link rel="stylesheet" href="style.css">

</head>
<body>

<div class="header">

<h1>VINS CAFE</h1>
</div>
<div class="bar">
 <a href="Restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</div>





</body>




</html>'
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  
  <title>Menu - The Hungry Hub</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="menu-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>

  <h1 class="page-title">South Indian Specialties</h1>

  <div class="menu-grid">

    <div class="menu-item"><img src="idly.png" alt="Idli Sambar"><p>Idli Sambar</p></div>
    <div class="menu-item"><img src="dosa.png" alt="Masala Dosa"><p>Masala Dosa</p></div>
    <div class="menu-item"><img src="vada.png" alt="Medu Vada"><p>Medu Vada</p></div>
    <div class="menu-item"><img src="onion.png" alt="Onion Uttapam"><p>Onion Uttapam</p></div>
    <div class="menu-item"><img src="pongal.png" alt="Ven Pongal"><p>Ven Pongal</p></div>
    <div class="menu-item"><img src="sambar.png" alt="Sambar Rice"><p>Sambar Rice</p></div>
  </div>
</body>
</html>
```
Administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  
  <title>Our Team</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="admin-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>

  <section class="team-section">
    <h2 style="text-align: center; color: white;">Meet Our Culinary Crew</h2>

    <div class="team-grid">

      <div class="team-member">
        <img src="chef1.png" alt="AARAV">
        <h3>VIJAY - Executive Chef</h3>
      </div>

      <div class="team-member">
        <img src="chef2.png" alt="SNEHA">
        <h3>EMMA - Pastry Chef</h3>
      </div>

      <div class="team-member">
        <img src="chef3.png" alt="MEERA">
        <h3>SELENA - Beverage Manager</h3>
      </div>

      <div class="team-member">
        <img src="chef4.png" alt="PRIYA">
        <h3>SAM - Guest Relations Officer</h3>
      </div>

    </div>
  </section>

</body>
</html>
```
Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
 
  <title>Contact Us</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body class="contact-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>

  <div class="contact-container">
    <div class="contact-info">
      <h1>We'd Love to Hear From You</h1>
      <p><i class="fas fa-map-marker-alt"></i> 55 Spice Avenue, Gourmet Town, GT 90210</p>
      <p><i class="fas fa-phone-alt"></i> +1 (987) 654-3210</p>
      <p><i class="fas fa-envelope"></i> support@tastehub.com</p>
      <p><i class="fas fa-clock"></i> Mon - Sun: 10:00 AM - 11:00 PM</p>
    </div>

    <div class="contact-form">
      <h2>Drop Us a Message</h2>

      <form>
        <input type="text" placeholder="Enter Your Full Name" required />
        <input type="email" placeholder="Enter Your Email Address" required />
        <textarea rows="5" placeholder="Write Your Message Here..."></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

</body>
</html>
```
style.css
```
<!DOCTYPE html>
<html lang="en">
<head>
 
  <title>Contact Us</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body class="contact-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>

  <div class="contact-container">
    <div class="contact-info">
      <h1>We'd Love to Hear From You</h1>
      <p><i class="fas fa-map-marker-alt"></i> 55 Spice Avenue, Gourmet Town, GT 90210</p>
      <p><i class="fas fa-phone-alt"></i> +1 (987) 654-3210</p>
      <p><i class="fas fa-envelope"></i> support@tastehub.com</p>
      <p><i class="fas fa-clock"></i> Mon - Sun: 10:00 AM - 11:00 PM</p>
    </div>

    <div class="contact-form">
      <h2>Drop Us a Message</h2>

      <form>
        <input type="text" placeholder="Enter Your Full Name" required />
        <input type="email" placeholder="Enter Your Email Address" required />
        <textarea rows="5" placeholder="Write Your Message Here..."></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-11-20 053938-1.png>)
![alt text](<Screenshot 2025-11-20 053951-1.png>)
![alt text](<Screenshot 2025-11-20 053959-1.png>)
![alt text](<Screenshot 2025-11-20 054007-1.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
