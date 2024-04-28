# Ex.07 Software Product Company Website
## Date: 28/04/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Product Development Company</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">HARIHARAN APPS</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="people.html">People</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h1>Welcome to Our Software Product Development Company</h1>
    </section>

    <section class="about">
        <h2>About Us</h2>
        <p>Welcome to HARIHARAN APPS, a leading software development company dedicated to creating innovative solutions for businesses of all sizes. With a team of experienced professionals, we specialize in delivering high-quality software products and services that drive growth and efficiency.</p>
        <p>Thank you for considering HARIHARAN APPS for your software development needs. We look forward to partnering with you and helping you achieve your business goals.</p>
    </section>
    

    <section class="featured-products">
        <h2>Featured Products</h2>
        <div class="product">
            <h3>Products</h3>
            <a href="products.html">Learn More</a>
        </div>
        <!-- Repeat the above structure for other featured products -->
    </section>

    <footer>
        <p>&copy; 2024 HARIHARAN. All rights reserved.</p>
    </footer>
</body>
</html>
```

products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">HARIHARAN APPS</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="people.html">People</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="products">
        <img src="images/product/products.png" alt="" style="display:block;margin: auto;width: 80%;margin-top: 10%;">
    </section>

    <footer>
        <p>&copy; 2024 HARIHARAN. All rights reserved.</p>
    </footer>
</body>
</html>
```

people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        #ceo{
            height: 200px;
        }
        body{
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">HARIHARAN APPS</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="people.html">People</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="people">
        <h1>Our Team</h1>
        <div class="person">
            <img src="images/people/hariharan.jpg" alt="Person 1" id="ceo">
            <h2>Hariharan</h2>
            <p>CEO</p>
        </div>
        <img src="images/people/team.png" alt="">
    </section>

    <footer>
        <p>&copy; 2024 HARIHARAN. All rights reserved.</p>
    </footer>
</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - HARIHARAN APPS</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        input , textarea{
            margin-top: 30px;
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">HARIHARAN APPS</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="people.html">People</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Contact us at:</p>
        <p>123 Main Street, City, Country</p>
        <p>Phone: 123-456-7890</p>
        <p>Email: info@example.com</p>
        
        <!-- Contact Form -->
        <h2>Send us a message</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 HARIHARAN. All rights reserved.</p>
    </footer>
</body>
</html>
```

styles.css
```
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Global Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #00205b;
}

header {
    background-color: #00205b;
    color: #fff;
    padding: 10px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 960px;
    margin: 0 auto;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

.banner {
    background-image: url('images/bg.jpg');
    background-size: cover;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    text-align: center;
}

.about,
.featured-products,
.contact {
    max-width: 960px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.product {
    margin-bottom: 20px;
}

.product img {
    max-width: 100%;
    border-radius: 8px;
}

.product h3 {
    margin-top: 10px;
}

footer {
    background-color: #00205b;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    position: fixed;
    bottom: 0%;
    width: 100%;
}
```


## OUTPUT:
![Screenshot (247)](https://github.com/hariharan0033/softweb/assets/125666185/021f86e8-ff10-4364-bb36-3fd528754658)

![Screenshot (248)](https://github.com/hariharan0033/softweb/assets/125666185/9069d9f6-fff9-4652-9cc0-5170ddd295ab)

![Screenshot (251)](https://github.com/hariharan0033/softweb/assets/125666185/3748904a-26c3-4a4b-93e4-442b9894f227)

![Screenshot (258)](https://github.com/hariharan0033/softweb/assets/125666185/501f3f5b-871b-4979-9b9b-9ce5539c848f)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
