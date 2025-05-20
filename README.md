# Project Responsive Web Design using Bootstrap
## Date:15/05/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
<head>
    
    <title>Pharmacy Company</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        header{
            background-image: url(2medlogo.png);
            background-repeat: no-repeat;
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-success">
        <a class="navbar-brand" href="#" font-family="Bradley Hand ITC">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" >
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="pharmacy.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="productpharm.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="pharmcontact.html">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://en.wikipedia.org/wiki/Pharmaceutical_industry#">About Us</a>
                </li>
            </ul>
        </div>
    </nav>

    <header class="jumbotron text-center bg-light">
        <h1 class="display-4" ><b>Welcome to Pharma.Co</b></h1><br><br>
        <p class="lead">Your trusted partner in healthcare and pharmaceutical solutions.</p><br><br>
        <a class="btn btn-dark btn-lg" href="#" role="button">Explore Products</a><br><br>
    </header>

    
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <h3>Quality Medicines</h3>
                <p>We provide high-quality and certified medicines for various health needs.</p>
            </div>
            <div class="col-md-4">
                <h3>24/7 Support</h3>
                <p>Our team is available round the clock to assist with your queries.</p>
            </div>
            <div class="col-md-4">
                <h3><b>Affordable Prices</b></h3>
                <p>We ensure competitive pricing without compromising on quality.</p>
            </div>
        </div>
    </div><br><br><br><br><br><br><br><br><br>

    
    <footer class="bg-success text-white text-center py-3 mt-4">
        <p>Designed and Developed by VIKASKUMAR M</p>
    </footer>

    
</body>
</html>
```
```
<html>
<head>
    <title>Pharm.co Product Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #007BFF;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product-info {
            flex: 1;
        }
        .product-info h1 {
            font-size: 2rem;
            margin: 0;
        }
        .product-info p {
            margin: 1rem 0;
            line-height: 1.5;
        }
        .price {
            font-size: 1.5rem;
            color: #007BFF;
        }
        .add-to-cart {
            background-color: #007BFF;
            color: white;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }
        .add-to-cart:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-success">
        <a class="navbar-brand" href="#" font-family="Bradley Hand ITC">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" >
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="pharmacy.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="productpharm.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="pharmcontact.html">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://en.wikipedia.org/wiki/Pharmaceutical_industry#">About Us</a>
                </li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <div class="product">
            <div class="product-image">
                <img src="2dolo.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Dolo 650</h1>
                <p>Paracetamol has antipyretic and analgesic, which 
                    helps in decreasing fever and pain, and it has a minimal anti-inflammatory action.</p>
                <p class="price">₹30</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2valium.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Valium</h1>
                <p>Diazepam is a medication that treats anxiety, seizures,
                   muscle spasms or twitches. It can also reduce the symptoms of alcohol withdrawal.</p>
                <p class="price">₹45</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2xanax.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Xanan</h1>
                <p> Anxiety disorders, including generalized anxiety disorder.
                     Panic disorder with or without agoraphobia.</p>
                <p class="price">₹70</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2ritalin.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Ritalin</h1>
                <p>Methylphenidate is a stimulant that treats attention-
                deficit/hyperactivity disorder (ADHD). It works by improving your focus and reducing impulsive behaviors.</p>
                <p class="price">₹85</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2heroin.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Heroin</h1>
                <p>Methadone is a synthetic opioid prescription
                     medication used as a replacement for heroin </p>
                <p class="price">₹152</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2adderalla.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Adderalla</h1>
                <p>It's most commonly used to treat attention deficit
                  hyperactivity disorder (ADHD). It's also used to treat narcolepsy.</p>
                <p class="price">₹142</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2cetirizine.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Cetirizine</h1>
                <p>Cetirizine is an antihistamine medication that 
                    treats allergy symptoms like itchy eyes, sneezing, a stuffy nose or hives</p>
                <p class="price">₹40</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2amoxicillin.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Amoxicillin</h1>
                <p>Amoxicillin is a penicillin antibiotic.
                    It can also be used together with other antibiotics and medicines to treat stomach ulcers.</p>
                <p class="price">₹168</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2betahistine.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Betahistine</h1>
                <p>Betahistine is a medicine used to treat the symptoms of Ménière's disease.</p>
                <p class="price">₹432</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
        <div class="product">
            <div class="product-image">
                <img src="2glimpride.jpeg" alt="Product Name">
            </div>
            <div class="product-info">
                <h1>Glimepride</h1>
                <p>Glimepiride is a medicine used to treat type 2 diabetes.
                   Type 2 diabetes is a condition where the body does not
                   make enough insulin, or the insulin that it makes does not work properly</p>
                <p class="price">₹575</p>
                <button class="add-to-cart">Add to Cart</button>
            </div>
        </div>
    </main>

    <footer class="header">
        <p>&copy; 2024 Pharm.co. All rights reserved.</p>
    </footer>
</body>
</html>
```
```
<html>
<head>
    
    <title>Pharmacy Company</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: white;
            color: #000000;
            padding: 5px 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: relative;
            height: 80px;
            overflow: hidden;
            
        }

        header nav a {
            padding-right: 10px;
            text-decoration: none;
            color: #000000;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .tblogo{
            display: flex;
            height: 120px;

        }

        .ltext{
            height: 95px;
            margin-top: 5%;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .contact-banner h1 {
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 2.5rem;
            color:white;
            background-image: url(bg2.jpg);
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
        }
        .contact-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 30px 15px;
            background: white;
            gap: 20px;
            background-color: #aaa9a9;
        }
        .contact-details, .contact-form {
            flex: 1;
            max-width: 500px;
            margin: 10px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 4px 4px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .contact-details h2, .contact-form h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #1f1714;
            text-align: center;
        }
        .contact-details p {
            margin: 10px 0;
            font-size: 1rem;
            color: #555;
        }
        .contact-details img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact-form textarea {
            height: 100px;
        }
        .contact-form button {
            width: 100%;
            padding: 10px;
            background: #ff5722;
            color: white;
            font-size: 1.1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .contact-form button:hover {
            background: #e64a19;
        }
        footer {
            background: rgb(4, 186, 95);
            color: rgb(0, 0, 0);
            text-align: center;
            padding: px 0;
            margin-top: 180px;
        }

        @media (max-width: 768px) {
            .contact-details, .contact-form {
                max-width: 100%;
            }

            .contact-banner h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-success">
        <a class="navbar-brand" href="#" font-family="Bradley Hand ITC">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" >
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="pharmacy.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="productpharm.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="pharmcontact.html">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://en.wikipedia.org/wiki/Pharmaceutical_industry#">About Us</a>
                </li>
            </ul>
        </div>
    </nav>

    <div class="contact-banner">
   
   <section class="contact-section">
        <div class="contact-details">
            <h2>Contact</h2>
            <img src="2contact.jpeg" alt="Contact Us">
            <p><strong>Phone:</strong> +91 9075005279</p>
            <p><strong>Email:</strong> pharmco@gmail.com</p>
            <p><strong>Opens:</strong> 24/7</p>
        </div>

        <div class="contact-form">
            <h2>Send Us a Message</h2>
            <form action="/submit-contact" method="POST">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required>

                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" placeholder="Enter your email address" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" placeholder="Your message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
   </div>    

    
    <footer class="bg-success text-white text-center py-3 mt-4">
        <p>Designed and Developed by VIKASKUMAR M</p>
    </footer>

    
</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/0b9ea4ad-44c4-40c2-bbfb-27c79cd0cb3d)
![image](https://github.com/user-attachments/assets/cd271a30-2916-44da-b8e4-e3f9102581e4)
![image](https://github.com/user-attachments/assets/6f3a4b19-d381-4524-8883-c2fecbc335f0)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
