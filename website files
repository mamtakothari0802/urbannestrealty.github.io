<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UrbanNest Realty - Surat | Premium Real Estate Solutions</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #1a5276;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #f8f9fa;
            --dark-color: #2c3e50;
            --success-color: #27ae60;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-top {
            background-color: var(--primary-color);
            color: white;
            padding: 8px 0;
            font-size: 14px;
        }
        
        .header-top .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .header-main {
            padding: 15px 0;
        }
        
        .header-main .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            font-size: 24px;
            font-weight: bold;
            color: var(--primary-color);
        }
        
        .logo i {
            margin-right: 10px;
            color: var(--secondary-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 25px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--dark-color);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--secondary-color);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://picsum.photos/seed/realestate/1600/800.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 20px;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--secondary-color);
            color: white;
            text-decoration: none;
            border-radius: 4px;
            font-weight: 600;
            transition: background-color 0.3s;
            border: none;
            cursor: pointer;
        }
        
        .btn:hover {
            background-color: var(--primary-color);
        }
        
        .btn-outline {
            background-color: transparent;
            border: 2px solid white;
            margin-left: 10px;
        }
        
        .btn-outline:hover {
            background-color: white;
            color: var(--primary-color);
        }
        
        /* Property Search Section */
        .property-search {
            background-color: var(--light-color);
            padding: 40px 0;
            margin-top: -40px;
            position: relative;
            z-index: 10;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .search-form {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }
        
        .form-group {
            flex: 1;
            min-width: 200px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
            color: var(--dark-color);
        }
        
        .form-group input,
        .form-group select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        
        /* Services Section */
        .services {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 36px;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .section-title p {
            font-size: 18px;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            padding: 30px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .service-card i {
            font-size: 48px;
            color: var(--secondary-color);
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: var(--primary-color);
        }
        
        /* Featured Properties Section */
        .featured-properties {
            background-color: var(--light-color);
            padding: 80px 0;
        }
        
        .properties-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .property-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .property-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .property-image {
            height: 220px;
            overflow: hidden;
        }
        
        .property-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .property-card:hover .property-image img {
            transform: scale(1.1);
        }
        
        .property-status {
            position: absolute;
            top: 15px;
            left: 15px;
            padding: 5px 10px;
            background-color: var(--success-color);
            color: white;
            font-size: 12px;
            border-radius: 4px;
            font-weight: 600;
        }
        
        .property-status.under-construction {
            background-color: var(--accent-color);
        }
        
        .property-content {
            padding: 25px;
        }
        
        .property-content h3 {
            font-size: 22px;
            margin-bottom: 10px;
            color: var(--primary-color);
        }
        
        .property-location {
            display: flex;
            align-items: center;
            color: #777;
            margin-bottom: 15px;
        }
        
        .property-location i {
            margin-right: 5px;
        }
        
        .property-features {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }
        
        .property-feature {
            display: flex;
            align-items: center;
        }
        
        .property-feature i {
            margin-right: 5px;
            color: var(--secondary-color);
        }
        
        .property-price {
            font-size: 22px;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .property-amenities {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 20px;
        }
        
        .amenity-tag {
            background-color: var(--light-color);
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            color: var(--dark-color);
        }
        
        /* Contact Section */
        .contact {
            padding: 80px 0;
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
        }
        
        .contact-info {
            padding: 20px;
        }
        
        .contact-info h3 {
            font-size: 24px;
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .contact-item {
            display: flex;
            margin-bottom: 20px;
        }
        
        .contact-item i {
            font-size: 20px;
            color: var(--secondary-color);
            margin-right: 15px;
            margin-top: 3px;
        }
        
        .contact-form {
            background-color: var(--light-color);
            padding: 30px;
            border-radius: 8px;
        }
        
        .contact-form h3 {
            font-size: 24px;
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        
        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 60px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 20px;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-column h3:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: var(--secondary-color);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 10px;
        }
        
        .footer-column ul li a {
            color: #bbb;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--secondary-color);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            color: white;
            transition: background-color 0.3s;
        }
        
        .social-links a:hover {
            background-color: var(--secondary-color);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bbb;
        }
        
        /* Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            z-index: 2000;
            overflow: auto;
        }
        
        .modal-content {
            background-color: white;
            margin: 5% auto;
            padding: 30px;
            width: 90%;
            max-width: 800px;
            border-radius: 8px;
            position: relative;
        }
        
        .close-modal {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 28px;
            cursor: pointer;
            color: #777;
        }
        
        .close-modal:hover {
            color: var(--primary-color);
        }
        
        .property-detail {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        
        .property-detail-images {
            grid-column: span 2;
        }
        
        .property-detail-images img {
            width: 100%;
            height: 400px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        
        .property-thumbnails {
            display: flex;
            gap: 10px;
        }
        
        .property-thumbnails img {
            width: 100px;
            height: 80px;
            object-fit: cover;
            border-radius: 4px;
            cursor: pointer;
            opacity: 0.7;
            transition: opacity 0.3s;
        }
        
        .property-thumbnails img:hover,
        .property-thumbnails img.active {
            opacity: 1;
        }
        
        .property-detail-info h2 {
            font-size: 28px;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .property-detail-price {
            font-size: 24px;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 20px;
        }
        
        .property-detail-features {
            margin-bottom: 20px;
        }
        
        .property-detail-features h4 {
            font-size: 18px;
            margin-bottom: 10px;
            color: var(--primary-color);
        }
        
        .property-detail-features ul {
            list-style: none;
            padding-left: 0;
        }
        
        .property-detail-features li {
            padding: 5px 0;
            border-bottom: 1px solid #eee;
        }
        
        .property-detail-features li i {
            color: var(--secondary-color);
            margin-right: 10px;
        }
        
        .property-detail-description {
            grid-column: span 2;
        }
        
        .property-detail-description h4 {
            font-size: 18px;
            margin-bottom: 10px;
            color: var(--primary-color);
        }
        
        /* Toast Notification */
        .toast {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: var(--success-color);
            color: white;
            padding: 15px 25px;
            border-radius: 4px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transform: translateY(100px);
            opacity: 0;
            transition: transform 0.3s, opacity 0.3s;
            z-index: 3000;
        }
        
        .toast.show {
            transform: translateY(0);
            opacity: 1;
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .contact-container {
                grid-template-columns: 1fr;
            }
            
            .property-detail {
                grid-template-columns: 1fr;
            }
            
            .property-detail-images {
                grid-column: span 1;
            }
            
            .property-detail-description {
                grid-column: span 1;
            }
        }
        
        @media (max-width: 768px) {
            .header-main .container {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }
            
            nav ul li {
                margin: 5px 10px;
            }
            
            .hero h1 {
                font-size: 36px;
            }
            
            .hero p {
                font-size: 18px;
            }
            
            .form-row {
                grid-template-columns: 1fr;
            }
            
            .properties-grid {
                grid-template-columns: 1fr;
            }
            
            .services-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-top">
            <div class="container">
                <div class="contact-info-top">
                    <i class="fas fa-phone"></i> +91 98765 43210
                    <span style="margin-left: 20px;"><i class="fas fa-envelope"></i> info@urbannestrealty.com</span>
                </div>
                <div class="working-hours">
                    <i class="fas fa-clock"></i> Mon-Sat: 10AM-7PM
                </div>
            </div>
        </div>
        <div class="header-main">
            <div class="container">
                <div class="logo">
                    <i class="fas fa-building"></i> UrbanNest Realty
                </div>
                <nav>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#properties">Properties</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Find Your Dream Property in Surat</h1>
            <p>UrbanNest Realty offers premium residential and commercial properties in Surat's most sought-after locations</p>
            <a href="#properties" class="btn">Explore Properties</a>
            <a href="#contact" class="btn btn-outline">Contact Us</a>
        </div>
    </section>

    <!-- Property Search Section -->
    <section class="property-search">
        <div class="container">
            <form class="search-form" id="propertySearchForm">
                <div class="form-group">
                    <label for="purpose">Purpose</label>
                    <select id="purpose" name="purpose">
                        <option value="">Select Purpose</option>
                        <option value="buy">Buy</option>
                        <option value="rent">Rent</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="property-type">Property Type</label>
                    <select id="property-type" name="property-type">
                        <option value="">Select Type</option>
                        <option value="residential">Residential</option>
                        <option value="commercial">Commercial</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="property-category">Category</label>
                    <select id="property-category" name="property-category">
                        <option value="">Select Category</option>
                        <option value="1bhk">1 BHK</option>
                        <option value="2bhk">2 BHK</option>
                        <option value="3bhk">3 BHK</option>
                        <option value="premium">Premium Apartments</option>
                        <option value="villa">Villa</option>
                        <option value="office">Office Space</option>
                        <option value="retail">Retail Shop</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="location">Location</label>
                    <select id="location" name="location">
                        <option value="">Select Location</option>
                        <option value="vesu">Vesu</option>
                        <option value="adajan">Adajan</option>
                        <option value="pal">Pal</option>
                        <option value="piplod">Piplod</option>
                        <option value="althan">Althan</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="budget">Budget</label>
                    <select id="budget" name="budget">
                        <option value="">Select Budget</option>
                        <option value="0-50">Below ₹50 Lakh</option>
                        <option value="50-100">₹50 Lakh - ₹1 Crore</option>
                        <option value="100-200">₹1 Crore - ₹2 Crore</option>
                        <option value="200-300">₹2 Crore - ₹3 Crore</option>
                        <option value="300+">Above ₹3 Crore</option>
                    </select>
                </div>
                <div class="form-group" style="display: flex; align-items: flex-end;">
                    <button type="submit" class="btn">Search Properties</button>
                </div>
            </form>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Services</h2>
                <p>We provide comprehensive real estate solutions tailored to your needs</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-home"></i>
                    <h3>Residential Properties</h3>
                    <p>From 1 BHK apartments to luxurious villas, we help you find your perfect home in Surat's prime locations.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-building"></i>
                    <h3>Commercial Properties</h3>
                    <p>Office spaces, retail shops, and showrooms in high-footfall areas to grow your business.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-handshake"></i>
                    <h3>Property Consulting</h3>
                    <p>Expert advice on property investments, market trends, and legal documentation.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>Investment Advisory</h3>
                    <p>Strategic guidance for real estate investments with high potential returns.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-key"></i>
                    <h3>Rental Solutions</h3>
                    <p>Find the perfect rental property or get your property listed for maximum visibility.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-users"></i>
                    <h3>Channel Partner</h3>
                    <p>We work as channel partners for multiple developers, offering you the best options.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Properties Section -->
    <section id="properties" class="featured-properties">
        <div class="container">
            <div class="section-title">
                <h2>Featured Properties</h2>
                <p>Explore our handpicked selection of premium properties in Surat</p>
            </div>
            <div class="properties-grid" id="propertiesGrid">
                <!-- Properties will be loaded here by JavaScript -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-title">
                <h2>Get In Touch</h2>
                <p>Our property consultants are ready to help you find your dream property</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Contact Information</h3>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h4>Head Office</h4>
                            <p>Vesu, Surat, Gujarat</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h4>Phone</h4>
                            <p>+91 98765 43210</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h4>Email</h4>
                            <p>info@urbannestrealty.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-clock"></i>
                        <div>
                            <h4>Working Hours</h4>
                            <p>Monday to Saturday: 10:00 AM - 7:00 PM</p>
                            <p>Sunday: Closed</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>Request a Site Visit</h3>
                    <form id="contactForm">
                        <div class="form-row">
                            <div class="form-group">
                                <label for="name">Full Name *</label>
                                <input type="text" id="name" name="name" required>
                            </div>
                            <div class="form-group">
                                <label for="phone">Phone Number *</label>
                                <input type="tel" id="phone" name="phone" required>
                            </div>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="purpose-contact">Purpose *</label>
                                <select id="purpose-contact" name="purpose-contact" required>
                                    <option value="">Select Purpose</option>
                                    <option value="buy">Buy</option>
                                    <option value="rent">Rent</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label for="property-type-contact">Property Type *</label>
                                <select id="property-type-contact" name="property-type-contact" required>
                                    <option value="">Select Type</option>
                                    <option value="residential">Residential</option>
                                    <option value="commercial">Commercial</option>
                                </select>
                            </div>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="property-category-contact">Category *</label>
                                <select id="property-category-contact" name="property-category-contact" required>
                                    <option value="">Select Category</option>
                                    <option value="1bhk">1 BHK</option>
                                    <option value="2bhk">2 BHK</option>
                                    <option value="3bhk">3 BHK</option>
                                    <option value="premium">Premium Apartments</option>
                                    <option value="villa">Villa</option>
                                    <option value="office">Office Space</option>
                                    <option value="retail">Retail Shop</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label for="preferred-area">Preferred Area *</label>
                                <select id="preferred-area" name="preferred-area" required>
                                    <option value="">Select Area</option>
                                    <option value="vesu">Vesu</option>
                                    <option value="adajan">Adajan</option>
                                    <option value="pal">Pal</option>
                                    <option value="piplod">Piplod</option>
                                    <option value="althan">Althan</option>
                                </select>
                            </div>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="budget-contact">Approximate Budget *</label>
                                <input type="text" id="budget-contact" name="budget-contact" placeholder="e.g., ₹1 Crore" required>
                            </div>
                            <div class="form-group">
                                <label for="visit-time">Preferred Site Visit Time *</label>
                                <input type="text" id="visit-time" name="visit-time" placeholder="e.g., Weekend Afternoon" required>
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="message">Additional Message</label>
                            <textarea id="message" name="message" placeholder="Any specific requirements..."></textarea>
                        </div>
                        <button type="submit" class="btn">Submit Request</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>About UrbanNest Realty</h3>
                    <p>UrbanNest Realty is a leading real estate consulting and brokerage firm in Surat, specializing in residential and commercial properties across prime locations.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#properties">Properties</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#contact">Contact Us</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Our Locations</h3>
                    <ul>
                        <li><a href="#">Vesu</a></li>
                        <li><a href="#">Adajan</a></li>
                        <li><a href="#">Pal</a></li>
                        <li><a href="#">Piplod</a></li>
                        <li><a href="#">Althan</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Info</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> Vesu, Surat, Gujarat</li>
                        <li><i class="fas fa-phone"></i> +91 98765 43210</li>
                        <li><i class="fas fa-envelope"></i> info@urbannestrealty.com</li>
                        <li><i class="fas fa-clock"></i> Mon-Sat: 10AM-7PM</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 UrbanNest Realty. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Property Detail Modal -->
    <div id="propertyModal" class="modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <div id="modalContent">
                <!-- Property details will be loaded here -->
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toast" class="toast">
        <span id="toastMessage">Message</span>
    </div>

    <script>
        // Property data
        const properties = [
            {
                id: 1,
                name: "Shree Galaxy Residency",
                location: "Vesu, Surat",
                type: "residential",
                category: "apartment",
                status: "under-construction",
                image: "https://picsum.photos/seed/galaxy/600/400.jpg",
                configurations: [
                    { type: "2 BHK", size: "1,150 sq.ft.", price: "₹72 lakh to ₹88 lakh" },
                    { type: "3 BHK", size: "1,480 sq.ft.", price: "₹92 lakh to ₹1.15 crore" }
                ],
                amenities: ["Covered parking", "Gym", "Children's play area", "Power backup", "Security"],
                description: "Shree Galaxy Residency offers premium residential apartments in the heart of Vesu, one of Surat's most sought-after locations. With modern amenities and spacious designs, these homes are perfect for families looking for comfort and convenience."
            },
            {
                id: 2,
                name: "Riverfront Heights",
                location: "Adajan, Surat",
                type: "residential",
                category: "apartment",
                status: "ready-to-move",
                image: "https://picsum.photos/seed/riverfront/600/400.jpg",
                configurations: [
                    { type: "2 BHK", size: "1,050 sq.ft.", price: "₹65 lakh to ₹82 lakh" },
                    { type: "3 BHK", size: "1,420 sq.ft.", price: "₹90 lakh to ₹1.1 crore" }
                ],
                amenities: ["Garden", "Indoor games", "Lift", "CCTV"],
                description: "Riverfront Heights is a ready-to-move residential project in Adajan, offering stunning views and a serene living environment. With well-designed apartments and essential amenities, it's an ideal choice for homebuyers."
            },
            {
                id: 3,
                name: "Palm Vista Villas",
                location: "Pal, Surat",
                type: "residential",
                category: "villa",
                status: "under-construction",
                image: "https://picsum.photos/seed/palmvista/600/400.jpg",
                configurations: [
                    { type: "4 BHK", size: "150 to 180 sq.yd.", price: "₹2.1 crore to ₹3.4 crore" }
                ],
                amenities: ["Gated community", "Clubhouse", "Landscape garden", "24x7 security"],
                description: "Palm Vista Villas offers luxurious independent villas in the peaceful locality of Pal. These spacious homes come with modern amenities and are perfect for those seeking privacy and exclusivity."
            },
            {
                id: 4,
                name: "Platinum Trade Centre",
                location: "Piplod, Surat",
                type: "commercial",
                category: "office",
                status: "ready-to-move",
                image: "https://picsum.photos/seed/platinum/600/400.jpg",
                configurations: [
                    { type: "Office/Shop", size: "550 sq.ft. to 1,800 sq.ft.", price: "₹48 lakh to ₹2.2 crore" }
                ],
                amenities: ["Business lounge", "High-speed lifts", "Power backup", "Visitor parking"],
                description: "Platinum Trade Centre is a premium commercial property in Piplod, offering ready-to-move office spaces and retail shops. With modern amenities and a prime location, it's perfect for businesses looking to establish a strong presence."
            },
            {
                id: 5,
                name: "Althan Business Square",
                location: "Althan, Surat",
                type: "commercial",
                category: "office",
                status: "under-construction",
                image: "https://picsum.photos/seed/althan/600/400.jpg",
                configurations: [
                    { type: "Office", size: "620 sq.ft. to 1,400 sq.ft.", price: "₹55 lakh to ₹1.9 crore" }
                ],
                amenities: ["Conference room", "Cafeteria", "Security", "Parking"],
                description: "Althan Business Square is an upcoming commercial project in Althan, designed to meet the needs of modern businesses. With well-planned office spaces and essential amenities, it's set to become a business hub in the area."
            }
        ];

        // DOM elements
        const propertiesGrid = document.getElementById('propertiesGrid');
        const propertyModal = document.getElementById('propertyModal');
        const modalContent = document.getElementById('modalContent');
        const closeModal = document.querySelector('.close-modal');
        const contactForm = document.getElementById('contactForm');
        const propertySearchForm = document.getElementById('propertySearchForm');
        const toast = document.getElementById('toast');
        const toastMessage = document.getElementById('toastMessage');

        // Initialize the page
        document.addEventListener('DOMContentLoaded', function() {
            renderProperties(properties);
            
            // Add smooth scrolling to navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        window.scrollTo({
                            top: target.offsetTop - 80,
                            behavior: 'smooth'
                        });
                    }
                });
            });
        });

        // Render properties
        function renderProperties(propertiesToRender) {
            propertiesGrid.innerHTML = '';
            
            propertiesToRender.forEach(property => {
                const propertyCard = document.createElement('div');
                propertyCard.className = 'property-card';
                
                const statusClass = property.status === 'ready-to-move' ? '' : 'under-construction';
                const statusText = property.status === 'ready-to-move' ? 'Ready to Move' : 'Under Construction';
                
                propertyCard.innerHTML = `
                    <div class="property-image" style="position: relative;">
                        <img src="${property.image}" alt="${property.name}">
                        <span class="property-status ${statusClass}">${statusText}</span>
                    </div>
                    <div class="property-content">
                        <h3>${property.name}</h3>
                        <div class="property-location">
                            <i class="fas fa-map-marker-alt"></i> ${property.location}
                        </div>
                        <div class="property-features">
                            ${property.configurations.map(config => `
                                <div class="property-feature">
                                    <i class="fas fa-home"></i> ${config.type}
                                </div>
                            `).join('')}
                        </div>
                        <div class="property-price">
                            ${property.configurations[0].price}
                        </div>
                        <div class="property-amenities">
                            ${property.amenities.slice(0, 3).map(amenity => `
                                <span class="amenity-tag">${amenity}</span>
                            `).join('')}
                        </div>
                        <button class="btn view-details" data-id="${property.id}">View Details</button>
                    </div>
                `;
                
                propertiesGrid.appendChild(propertyCard);
            });
            
            // Add event listeners to view details buttons
            document.querySelectorAll('.view-details').forEach(button => {
                button.addEventListener('click', function() {
                    const propertyId = parseInt(this.getAttribute('data-id'));
                    showPropertyDetails(propertyId);
                });
            });
        }

        // Show property details in modal
        function showPropertyDetails(propertyId) {
            const property = properties.find(p => p.id === propertyId);
            if (!property) return;
            
            const statusClass = property.status === 'ready-to-move' ? '' : 'under-construction';
            const statusText = property.status === 'ready-to-move' ? 'Ready to Move' : 'Under Construction';
            
            modalContent.innerHTML = `
                <div class="property-detail">
                    <div class="property-detail-images">
                        <img src="${property.image}" alt="${property.name}" id="mainImage">
                        <div class="property-thumbnails">
                            <img src="${property.image}" alt="${property.name}" class="active" onclick="changeImage(this)">
                            <img src="https://picsum.photos/seed/${property.name}1/600/400.jpg" alt="${property.name}" onclick="changeImage(this)">
                            <img src="https://picsum.photos/seed/${property.name}2/600/400.jpg" alt="${property.name}" onclick="changeImage(this)">
                            <img src="https://picsum.photos/seed/${property.name}3/600/400.jpg" alt="${property.name}" onclick="changeImage(this)">
                        </div>
                    </div>
                    <div class="property-detail-info">
                        <h2>${property.name}</h2>
                        <div class="property-location">
                            <i class="fas fa-map-marker-alt"></i> ${property.location}
                        </div>
                        <span class="property-status ${statusClass}">${statusText}</span>
                        <div class="property-detail-price">
                            Starting from ${property.configurations[0].price}
                        </div>
                        <div class="property-detail-features">
                            <h4>Configurations</h4>
                            <ul>
                                ${property.configurations.map(config => `
                                    <li><i class="fas fa-check-circle"></i> ${config.type} - ${config.size} - ${config.price}</li>
                                `).join('')}
                            </ul>
                        </div>
                        <div class="property-detail-features">
                            <h4>Amenities</h4>
                            <ul>
                                ${property.amenities.map(amenity => `
                                    <li><i class="fas fa-check-circle"></i> ${amenity}</li>
                                `).join('')}
                            </ul>
                        </div>
                        <button class="btn" onclick="requestSiteVisit(${property.id})">Request Site Visit</button>
                    </div>
                    <div class="property-detail-description">
                        <h4>Description</h4>
                        <p>${property.description}</p>
                    </div>
                </div>
            `;
            
            propertyModal.style.display = 'block';
        }

        // Change main image in modal
        function changeImage(thumbnail) {
            const mainImage = document.getElementById('mainImage');
            mainImage.src = thumbnail.src;
            
            // Update active thumbnail
            document.querySelectorAll('.property-thumbnails img').forEach(img => {
                img.classList.remove('active');
            });
            thumbnail.classList.add('active');
        }

        // Close modal
        closeModal.addEventListener('click', function() {
            propertyModal.style.display = 'none';
        });

        window.addEventListener('click', function(event) {
            if (event.target === propertyModal) {
                propertyModal.style.display = 'none';
            }
        });

        // Handle contact form submission
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form data
            const formData = new FormData(contactForm);
            const data = {};
            formData.forEach((value, key) => {
                data[key] = value;
            });
            
            // Show success message
            showToast('Your request has been submitted successfully! Our property consultant will contact you soon.');
            
            // Reset form
            contactForm.reset();
        });

        // Handle property search form submission
        propertySearchForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form data
            const formData = new FormData(propertySearchForm);
            const filters = {};
            formData.forEach((value, key) => {
                if (value) filters[key] = value;
            });
            
            // Filter properties based on search criteria
            let filteredProperties = properties;
            
            if (filters.purpose) {
                // For demo purposes, we'll assume all properties are for sale
                // In a real application, you would have rental properties as well
            }
            
            if (filters['property-type']) {
                filteredProperties = filteredProperties.filter(p => p.type === filters['property-type']);
            }
            
            if (filters.location) {
                filteredProperties = filteredProperties.filter(p => 
                    p.location.toLowerCase().includes(filters.location.toLowerCase())
                );
            }
            
            if (filters.budget) {
                // This is a simplified filter for demo purposes
                // In a real application, you would have more sophisticated filtering
                const budgetRange = filters.budget.split('-');
                if (budgetRange[0] === '0') {
                    filteredProperties = filteredProperties.filter(p => 
                        !p.configurations[0].price.includes('crore')
                    );
                } else if (budgetRange[0] === '50') {
                    filteredProperties = filteredProperties.filter(p => 
                        p.configurations[0].price.includes('lakh') && 
                        !p.configurations[0].price.includes('1.1') &&
                        !p.configurations[0].price.includes('1.15')
                    );
                } else if (budgetRange[0] === '100') {
                    filteredProperties = filteredProperties.filter(p => 
                        p.configurations[0].price.includes('crore') || 
                        p.configurations[0].price.includes('1.1') ||
                        p.configurations[0].price.includes('1.15')
                    );
                }
            }
            
            // Render filtered properties
            renderProperties(filteredProperties);
            
            // Scroll to properties section
            document.getElementById('properties').scrollIntoView({ behavior: 'smooth' });
            
            // Show message if no properties found
            if (filteredProperties.length === 0) {
                showToast('No properties found matching your criteria. Please try different filters.');
            }
        });

        // Request site visit
        function requestSiteVisit(propertyId) {
            const property = properties.find(p => p.id === propertyId);
            if (!property) return;
            
            // Close modal
            propertyModal.style.display = 'none';
            
            // Scroll to contact form
            document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
            
            // Pre-fill form with property information
            document.getElementById('message').value = `I'm interested in ${property.name} at ${property.location}.`;
            
            // Show message
            showToast('Please fill in your details to request a site visit.');
        }

        // Show toast notification
        function showToast(message) {
            toastMessage.textContent = message;
            toast.classList.add('show');
            
            setTimeout(() => {
                toast.classList.remove('show');
            }, 5000);
        }
    </script>
</body>
</html>
