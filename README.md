<!DOCTYPE html>
<html lang="en-IN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Hyderabad's ultimate food guide - Discover best restaurants, hotels, street food spots and authentic recipes from the City of Pearls">
    <meta name="keywords" content="Hyderabad food, best restaurants Hyderabad, street food Hyderabad, Hyderabadi recipes, biryani, haleem, Irani chai, food blog India">
    <meta name="author" content="Hyderabad Food Guide">
    <meta name="geo.region" content="IN-TG">
    <meta name="geo.placename" content="Hyderabad">
    <link rel="canonical" href="https://www.hyderabadfoodguide.com">
    <meta property="og:title" content="Hyderabad Food Guide | Restaurants, Street Food & Recipes">
    <meta property="og:description" content="Discover the best food in Hyderabad - from luxury hotels to hidden street food gems and authentic recipes">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.hyderabadfoodguide.com">
    <meta property="og:image" content="https://www.hyderabadfoodguide.com/images/hyderabad-food-og.jpg">
    <meta property="og:site_name" content="Hyderabad Food Guide">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Hyderabad Food Guide | Restaurants, Street Food & Recipes">
    <meta name="twitter:description" content="Discover the best food in Hyderabad - from luxury hotels to hidden street food gems and authentic recipes">
    <meta name="twitter:image" content="https://www.hyderabadfoodguide.com/images/hyderabad-food-twitter.jpg">
    <link rel="icon" href="/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite",
      "name": "Hyderabad Food Guide",
      "url": "https://www.hyderabadfoodguide.com",
      "potentialAction": {
        "@type": "SearchAction",
        "target": "https://www.hyderabadfoodguide.com/search?q={search_term_string}",
        "query-input": "required name=search_term_string"
      }
    }
    </script>
    <title>Hyderabad Food Guide | Restaurants, Street Food & Recipes</title>
    <style>
        :root {
            --primary-color: #FF6B6B;
            --secondary-color: #4ECDC4;
            --accent-color: #FFE66D;
            --dark-color: #292F36;
            --light-color: #F7FFF7;
            --text-color: #333;
            --text-light: #777;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-color);
        }
        
        a {
            text-decoration: none;
            color: var(--primary-color);
            transition: all 0.3s ease;
        }
        
        a:hover {
            color: var(--dark-color);
        }
        
        img {
            max-width: 100%;
            height: auto;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: var(--primary-color);
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background-color: var(--dark-color);
            color: white;
            transform: translateY(-2px);
        }
        
        .section-title {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: var(--dark-color);
            position: relative;
            padding-bottom: 10px;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 60px;
            height: 3px;
            background-color: var(--primary-color);
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary-color);
        }
        
        .logo span {
            color: var(--dark-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            color: var(--dark-color);
            font-weight: 500;
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        .mobile-menu-btn {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1585032226651-759b368d7246?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        .search-box {
            max-width: 600px;
            margin: 0 auto;
            position: relative;
        }
        
        .search-box input {
            width: 100%;
            padding: 15px 20px;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
        }
        
        .search-box button {
            position: absolute;
            right: 5px;
            top: 5px;
            background-color: var(--primary-color);
            color: white;
            border: none;
            border-radius: 50px;
            padding: 10px 20px;
            cursor: pointer;
        }
        
        /* Search Results */
        .search-results {
            position: absolute;
            top: 100%;
            left: 0;
            right: 0;
            background: white;
            border-radius: 0 0 5px 5px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            z-index: 100;
            display: none;
        }

        .search-result-item {
            display: block;
            padding: 10px 15px;
            color: var(--text-color);
            border-bottom: 1px solid #eee;
        }

        .search-result-item:hover {
            background-color: #f9f9f9;
        }

        .search-result-type {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 2px 5px;
            border-radius: 3px;
            font-size: 0.8rem;
            margin-right: 10px;
        }

        /* Ad Banner */
        .ad-banner {
            background-color: #f5f5f5;
            padding: 20px;
            text-align: center;
            margin: 30px 0;
            border-radius: 5px;
        }
        
        /* Featured Sections */
        .featured-section {
            padding: 60px 0;
        }
        
        .section-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
        }
        
        .view-all {
            color: var(--primary-color);
            font-weight: 500;
        }
        
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 30px;
        }
        
        .card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-10px);
        }
        
        .card-img {
            height: 200px;
            overflow: hidden;
        }
        
        .card-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .card:hover .card-img img {
            transform: scale(1.1);
        }
        
        .card-content {
            padding: 20px;
        }
        
        .card-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        
        .card-meta {
            display: flex;
            justify-content: space-between;
            color: var(--text-light);
            font-size: 0.9rem;
            margin-bottom: 15px;
        }
        
        .card-excerpt {
            margin-bottom: 15px;
            color: var(--text-light);
        }
        
        /* Area Guide Section */
        .area-guide {
            background-color: var(--dark-color);
            color: white;
            padding: 60px 0;
        }
        
        .area-guide .section-title {
            color: white;
        }
        
        .area-guide .section-title::after {
            background-color: var(--accent-color);
        }
        
        .area-tabs {
            display: flex;
            margin-bottom: 30px;
            overflow-x: auto;
            padding-bottom: 10px;
        }
        
        .area-tab {
            padding: 10px 20px;
            background-color: rgba(255, 255, 255, 0.1);
            margin-right: 10px;
            border-radius: 5px;
            cursor: pointer;
            white-space: nowrap;
        }
        
        .area-tab.active {
            background-color: var(--primary-color);
        }
        
        .area-content {
            display: none;
        }
        
        .area-content.active {
            display: block;
        }
        
        .area-list {
            columns: 3;
            column-gap: 30px;
        }
        
        .area-list li {
            margin-bottom: 10px;
            break-inside: avoid;
        }
        
        /* Recipe Section */
        .recipe-card {
            position: relative;
        }
        
        .recipe-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background-color: var(--accent-color);
            color: var(--dark-color);
            padding: 5px 10px;
            border-radius: 5px;
            font-weight: 600;
            font-size: 0.8rem;
        }
        
        /* Newsletter Section */
        .newsletter {
            background-color: var(--secondary-color);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .newsletter .section-title {
            color: white;
        }
        
        .newsletter .section-title::after {
            background-color: white;
        }
        
        .newsletter-form {
            max-width: 500px;
            margin: 0 auto;
            display: flex;
        }
        
        .newsletter-form input {
            flex: 1;
            padding: 15px;
            border: none;
            border-radius: 5px 0 0 5px;
            font-size: 1rem;
        }
        
        .newsletter-form button {
            background-color: var(--dark-color);
            color: white;
            border: none;
            padding: 0 20px;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
        }
        
        /* Comments Section */
        .comments-section {
            padding: 60px 0;
        }
        
        .comment-form {
            margin-bottom: 40px;
        }
        
        .comment-form h3 {
            margin-bottom: 20px;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
        }
        
        .form-group textarea {
            min-height: 150px;
        }
        
        .comments-list {
            margin-top: 40px;
        }
        
        .comment {
            display: flex;
            margin-bottom: 30px;
            padding-bottom: 30px;
            border-bottom: 1px solid #eee;
        }
        
        .comment-avatar {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 20px;
            flex-shrink: 0;
        }
        
        .comment-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .comment-content {
            flex: 1;
        }
        
        .comment-meta {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        
        .comment-author {
            font-weight: 600;
            color: var(--dark-color);
        }
        
        .comment-date {
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        .comment-text {
            color: var(--text-color);
            line-height: 1.7;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 60px 0 20px;
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-col h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 40px;
            height: 2px;
            background-color: var(--primary-color);
        }
        
        .footer-col ul {
            list-style: none;
        }
        
        .footer-col ul li {
            margin-bottom: 10px;
        }
        
        .footer-col ul li a {
            color: #bbb;
        }
        
        .footer-col ul li a:hover {
            color: white;
            padding-left: 5px;
        }
        
        .social-links {
            display: flex;
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
            margin-right: 10px;
            color: white;
        }
        
        .social-links a:hover {
            background-color: var(--primary-color);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bbb;
            font-size: 0.9rem;
        }

        /* Loading States */
        .loading {
            position: relative;
            min-height: 100px;
        }

        .loading::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 30px;
            height: 30px;
            border: 3px solid rgba(0,0,0,0.1);
            border-radius: 50%;
            border-top-color: var(--primary-color);
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: translate(-50%, -50%) rotate(360deg); }
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .area-list {
                columns: 2;
            }
        }
        
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                text-align: center;
            }
            
            nav {
                margin-top: 20px;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .newsletter-form {
                flex-direction: column;
            }
            
            .newsletter-form input {
                border-radius: 5px;
                margin-bottom: 10px;
            }
            
            .newsletter-form button {
                border-radius: 5px;
                padding: 15px;
            }
        }
        
        @media (max-width: 576px) {
            .mobile-menu-btn {
                display: block;
            }
            
            nav {
                display: none;
                width: 100%;
                margin-top: 15px;
            }
            
            nav.active {
                display: block;
            }
            
            nav ul {
                flex-direction: column;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .hero {
                padding: 80px 20px;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .card-grid {
                grid-template-columns: 1fr;
            }
            
            .area-list {
                columns: 1;
            }
            
            .comment {
                flex-direction: column;
            }
            
            .comment-avatar {
                margin-bottom: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <a href="index.html" class="logo">Hyderabad<span>Food</span></a>
            
            <div class="mobile-menu-btn">
                <i class="fas fa-bars"></i>
            </div>
            
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="restaurants.html">Restaurants</a></li>
                    <li><a href="street-food.html">Street Food</a></li>
                    <li><a href="recipes.html">Recipes</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Discover Hyderabad's Culinary Treasures</h1>
            <p>From legendary biryani spots to hidden street food gems, explore the best food experiences in the City of Pearls</p>
            
            <div class="search-box">
                <input type="text" id="mainSearch" placeholder="Search for restaurants, street food or recipes...">
                <button onclick="performSearch()"><i class="fas fa-search"></i></button>
                <div id="searchResults" class="search-results"></div>
            </div>
        </div>
    </section>
    
    <!-- Ad Banner -->
    <div class="container">
        <div class="ad-banner">
            <!-- Google AdSense Ad Unit -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX"
                 crossorigin="anonymous"></script>
            <!-- Top Banner Ad -->
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="XXXXXXXXXX"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </div>
    
    <!-- Featured Restaurants -->
    <section class="featured-section">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Featured Restaurants</h2>
                <a href="restaurants.html" class="view-all">View All</a>
            </div>
            
            <div class="card-grid" id="featuredRestaurants">
                <!-- Content loaded via JavaScript -->
            </div>
        </div>
    </section>
    
    <!-- Mid-Page Ad Banner -->
    <div class="container">
        <div class="ad-banner">
            <!-- Google AdSense Rectangle Ad -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX"
                 crossorigin="anonymous"></script>
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-format="fluid"
                 data-ad-layout-key="-fb+5w+4e-db+86"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="XXXXXXXXXX"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </div>
    
    <!-- Street Food Section -->
    <section class="featured-section">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">old gems</h2>
                <a href="street-food.html" class="view-all">View All</a>
            </div>
            
            <div class="card-grid" id="streetFoodSpots">
                <!-- Content loaded via JavaScript -->
            </div>
        </div>
    </section>
    
    <!-- Area Guide Section -->
    <section class="area-guide">
        <div class="container">
            <h2 class="section-title">Food Guide by Area</h2>
            <p>Explore the best dining options neighborhood by neighborhood</p>
            
            <div class="area-tabs">
                <div class="area-tab active" data-area="central">Central Hyderabad</div>
                <div class="area-tab" data-area="west">West Hyderabad</div>
                <div class="area-tab" data-area="east">East Hyderabad</div>
                <div class="area-tab" data-area="north">North Hyderabad</div>
                <div class="area-tab" data-area="south">South Hyderabad</div>
            </div>
            
            <div class="area-content active" id="central-content">
                <h3>Best Restaurants & Street Food in Central Hyderabad</h3>
                <ul class="area-list" id="central-list">
                    <!-- Content loaded via JavaScript -->
                </ul>
            </div>
            
            <div class="area-content" id="west-content">
                <h3>Best Restaurants & Street Food in West Hyderabad</h3>
                <ul class="area-list" id="west-list">
                    <!-- Content loaded via JavaScript -->
                </ul>
            </div>
            
            <div class="area-content" id="east-content">
                <h3>Best Restaurants & Street Food in East Hyderabad</h3>
                <ul class="area-list" id="east-list">
                    <!-- Content loaded via JavaScript -->
                </ul>
            </div>
            
            <div class="area-content" id="north-content">
                <h3>Best Restaurants & Street Food in North Hyderabad</h3>
                <ul class="area-list" id="north-list">
                    <!-- Content loaded via JavaScript -->
                </ul>
            </div>
            
            <div class="area-content" id="south-content">
                <h3>Best Restaurants & Street Food in South Hyderabad</h3>
                <ul class="area-list" id="south-list">
                    <!-- Content loaded via JavaScript -->
                </ul>
            </div>
        </div>
    </section>
    
    <!-- Recipes Section -->
    <section class="featured-section">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Authentic Hyderabadi Recipes</h2>
                <a href="recipes.html" class="view-all">View All</a>
            </div>
            
            <div class="card-grid" id="featuredRecipes">
                <!-- Content loaded via JavaScript -->
            </div>
        </div>
    </section>
    
    <!-- Newsletter Section -->
    <section class="newsletter">
        <div class="container">
            <h2 class="section-title">Get Weekly Food Updates</h2>
            <p>Subscribe to our newsletter for the latest restaurant reviews, street food discoveries and exclusive recipes</p>
            
            <form class="newsletter-form" id="newsletterForm">
                <input type="email" id="subscriberEmail" placeholder="Your email address" required>
                <button type="submit">Subscribe</button>
                <div id="newsletterMessage"></div>
            </form>
        </div>
    </section>
    
    <!-- Comments Section -->
    <section class="comments-section">
        <div class="container">
            <h2 class="section-title">Share Your Food Experiences</h2>
            
            <div class="comment-form">
                <h3>Leave a Comment</h3>
                <form id="commentForm">
                    <input type="hidden" id="pageUrl" value="index.html">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email (will not be published)</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="comment">Your Comment</label>
                        <textarea id="comment" name="comment" required></textarea>
                    </div>
                    <button type="submit" class="btn">Post Comment</button>
                </form>
            </div>
            
            <div class="comments-list" id="commentsContainer">
                <!-- Comments loaded via JavaScript -->
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>Hyderabad Food Guide</h3>
                    <p>Your ultimate resource for discovering the best food experiences in Hyderabad - from luxury hotels to hidden street food gems.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-pinterest"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="restaurants.html">Restaurants</a></li>
                        <li><a href="street-food.html">Street Food</a></li>
                        <li><a href="recipes.html">Recipes</a></li>
                        <li><a href="about.html">About Us</a></li>
                        <li><a href="contact.html">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Popular Areas</h3>
                    <ul>
                        <li><a href="#">Banjara Hills</a></li>
                        <li><a href="#">Jubilee Hills</a></li>
                        <li><a href="#">Secunderabad</a></li>
                        <li><a href="#">Charminar</a></li>
                        <li><a href="#">Hitech City</a></li>
                        <li><a href="#">Gachibowli</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Contact Us</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> 123 Food Street, Hyderabad</li>
                        <li><i class="fas fa-phone"></i> +91 9876543210</li>
                        <li><i class="fas fa-envelope"></i> info@hyderabadfoodguide.com</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Hyderabad Food Guide. All Rights Reserved. | <a href="privacy.html">Privacy Policy</a> | <a href="terms.html">Terms of Service</a></p>
            </div>
        </div>
    </footer>
    
    <!-- JavaScript -->
    <script>
        // Sample data for demonstration
        const sampleData = {
            restaurants: [
                {
                    id: 1,
                    name: "Paradise Biryani",
                    location: "Secunderabad",
                    description: "The legendary biryani that put Hyderabad on the culinary map. Must-try: Hyderabadi Dum Biryani.",
                    price_range: "₹₹₹",
                    image_url: "https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 2,
                    name: "Bawarchi",
                    location: "RTC Cross Roads",
                    description: "Famous for its flavorful biryanis and generous portions. Don't miss their mutton biryani and mirchi ka salan.",
                    price_range: "₹₹",
                    image_url: "https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 3,
                    name: "Ohri's Jiva Imperia",
                    location: "Banjara Hills",
                    description: "Upscale dining with a mix of Indian and international cuisines. Perfect for special occasions.",
                    price_range: "₹₹₹₹",
                    image_url: "https://images.unsplash.com/photo-1551218370-a5c8a333ed84?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                }
            ],
            streetFood: [
                {
                    id: 1,
                    name: "Irani Chai at Nimrah Café",
                    location: "Charminar",
                    description: "The iconic Irani chai with Osmania biscuits is a must-try Hyderabad experience near Charminar.",
                    specialty: "Irani Chai & Osmania Biscuits",
                    image_url: "https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 2,
                    name: "Pista House Haleem",
                    location: "Nampally",
                    description: "The best haleem in town, especially during Ramadan. Rich, flavorful and absolutely addictive.",
                    specialty: "Haleem",
                    image_url: "https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 3,
                    name: "Shah Ghouse Kebabs",
                    location: "Jubilee Hills",
                    description: "Juicy, flavorful kebabs that melt in your mouth. The mutton seekh kebabs are legendary.",
                    specialty: "Kebabs",
                    image_url: "https://images.unsplash.com/photo-1563379091339-03b21ab2445b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                }
            ],
            recipes: [
                {
                    id: 1,
                    title: "Hyderabadi Dum Biryani",
                    prep_time: "30 mins",
                    difficulty: "Medium",
                    description: "The world-famous Hyderabadi biryani with layers of fragrant rice and perfectly spiced meat, cooked to perfection using the dum method.",
                    image_url: "https://images.unsplash.com/photo-1589301760014-d929f3979dbc?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 2,
                    title: "Hyderabadi Haleem",
                    prep_time: "2 hours",
                    difficulty: "Difficult",
                    description: "The rich, slow-cooked stew made with wheat, barley, lentils and meat that's a Ramadan specialty in Hyderabad.",
                    image_url: "https://images.unsplash.com/photo-1601050690597-df0568f70950?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                },
                {
                    id: 3,
                    title: "Authentic Irani Chai",
                    prep_time: "20 mins",
                    difficulty: "Easy",
                    description: "The creamy, sweet tea that's a Hyderabad institution, best paired with Osmania biscuits.",
                    image_url: "https://images.unsplash.com/photo-1606491956689-2ea866880c84?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                }
            ],
            areaLists: {
                central: [
                    "Paradise Biryani - Secunderabad",
                    "Café Bahar - Basheerbagh",
                    "Shadab - High Court Road",
                    "Nimrah Café - Charminar",
                    "Pista House - Nampally",
                    "Grand Hotel - Abids",
                    "Bawarchi - RTC Cross Roads",
                    "Sarvi - Narayanguda",
                    "Shah Ghouse - Tolichowki",
                    "Hotel Shadab - Old City"
                ],
                west: [
                    "Ohri's Jiva Imperia - Banjara Hills",
                    "Taj Krishna - Banjara Hills",
                    "Barbeque Nation - Jubilee Hills",
                    "Absolute Barbecue - Jubilee Hills",
                    "Chutneys - Banjara Hills",
                    "Eat India Company - Jubilee Hills",
                    "Mekong - Banjara Hills",
                    "The Fisherman's Wharf - Jubilee Hills",
                    "Ming's Court - Banjara Hills",
                    "Flechazo - Jubilee Hills
