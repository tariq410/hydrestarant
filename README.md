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
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://www.hyderabadfoodguide.com">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="Hyderabad Food Guide | Restaurants, Street Food & Recipes">
    <meta property="og:description" content="Discover the best food in Hyderabad - from luxury hotels to hidden street food gems and authentic recipes">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.hyderabadfoodguide.com">
    <meta property="og:image" content="https://www.hyderabadfoodguide.com/images/hyderabad-food-og.jpg">
    <meta property="og:site_name" content="Hyderabad Food Guide">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Hyderabad Food Guide | Restaurants, Street Food & Recipes">
    <meta name="twitter:description" content="Discover the best food in Hyderabad - from luxury hotels to hidden street food gems and authentic recipes">
    <meta name="twitter:image" content="https://www.hyderabadfoodguide.com/images/hyderabad-food-twitter.jpg">
    
    <!-- Favicon -->
    <link rel="icon" href="/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    
    <!-- Structured Data / Schema Markup -->
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
    
    <!-- CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Global Styles */
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
                <input type="text" placeholder="Search for restaurants, street food or recipes...">
                <button><i class="fas fa-search"></i></button>
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
            
            <div class="card-grid">
                <!-- Restaurant Card 1 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Paradise Restaurant">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Paradise Biryani</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> Secunderabad</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹₹₹</span>
                        </div>
                        <p class="card-excerpt">The legendary biryani that put Hyderabad on the culinary map. Must-try: Hyderabadi Dum Biryani.</p>
                        <a href="paradise-biryani.html" class="btn">Read More</a>
                    </div>
                </div>
                
                <!-- Restaurant Card 2 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Bawarchi Restaurant">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Bawarchi</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> RTC Cross Roads</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹₹</span>
                        </div>
                        <p class="card-excerpt">Famous for its flavorful biryanis and generous portions. Don't miss their mutton biryani and mirchi ka salan.</p>
                        <a href="bawarchi.html" class="btn">Read More</a>
                    </div>
                </div>
                
                <!-- Restaurant Card 3 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1551218370-a5c8a333ed84?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Ohri's Restaurant">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Ohri's Jiva Imperia</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> Banjara Hills</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹₹₹₹</span>
                        </div>
                        <p class="card-excerpt">Upscale dining with a mix of Indian and international cuisines. Perfect for special occasions.</p>
                        <a href="ohris-jiva.html" class="btn">Read More</a>
                    </div>
                </div>
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
                <h2 class="section-title">Street Food Hotspots</h2>
                <a href="street-food.html" class="view-all">View All</a>
            </div>
            
            <div class="card-grid">
                <!-- Street Food Card 1 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Irani Chai">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Irani Chai at Nimrah Café</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> Charminar</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹</span>
                        </div>
                        <p class="card-excerpt">The iconic Irani chai with Osmania biscuits is a must-try Hyderabad experience near Charminar.</p>
                        <a href="nimrah-cafe.html" class="btn">Read More</a>
                    </div>
                </div>
                
                <!-- Street Food Card 2 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Haleem">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Pista House Haleem</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> Nampally</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹₹</span>
                        </div>
                        <p class="card-excerpt">The best haleem in town, especially during Ramadan. Rich, flavorful and absolutely addictive.</p>
                        <a href="pista-house.html" class="btn">Read More</a>
                    </div>
                </div>
                
                <!-- Street Food Card 3 -->
                <div class="card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1563379091339-03b21ab2445b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Kebabs">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Shah Ghouse Kebabs</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-map-marker-alt"></i> Jubilee Hills</span>
                            <span><i class="fas fa-rupee-sign"></i> ₹₹</span>
                        </div>
                        <p class="card-excerpt">Juicy, flavorful kebabs that melt in your mouth. The mutton seekh kebabs are legendary.</p>
                        <a href="shah-ghouse.html" class="btn">Read More</a>
                    </div>
                </div>
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
                <ul class="area-list">
                    <li><a href="#">Paradise Biryani - Secunderabad</a></li>
                    <li><a href="#">Café Bahar - Basheerbagh</a></li>
                    <li><a href="#">Shadab - High Court Road</a></li>
                    <li><a href="#">Nimrah Café - Charminar</a></li>
                    <li><a href="#">Pista House - Nampally</a></li>
                    <li><a href="#">Grand Hotel - Abids</a></li>
                    <li><a href="#">Bawarchi - RTC Cross Roads</a></li>
                    <li><a href="#">Sarvi - Narayanguda</a></li>
                    <li><a href="#">Shah Ghouse - Tolichowki</a></li>
                    <li><a href="#">Hotel Shadab - Old City</a></li>
                </ul>
            </div>
            
            <div class="area-content" id="west-content">
                <h3>Best Restaurants & Street Food in West Hyderabad</h3>
                <ul class="area-list">
                    <li><a href="#">Ohri's Jiva Imperia - Banjara Hills</a></li>
                    <li><a href="#">Taj Krishna - Banjara Hills</a></li>
                    <li><a href="#">Barbeque Nation - Jubilee Hills</a></li>
                    <li><a href="#">Absolute Barbecue - Jubilee Hills</a></li>
                    <li><a href="#">Chutneys - Banjara Hills</a></li>
                    <li><a href="#">Eat India Company - Jubilee Hills</a></li>
                    <li><a href="#">Mekong - Banjara Hills</a></li>
                    <li><a href="#">The Fisherman's Wharf - Jubilee Hills</a></li>
                    <li><a href="#">Ming's Court - Banjara Hills</a></li>
                    <li><a href="#">Flechazo - Jubilee Hills</a></li>
                </ul>
            </div>
            
            <div class="area-content" id="east-content">
                <h3>Best Restaurants & Street Food in East Hyderabad</h3>
                <ul class="area-list">
                    <li><a href="#">Ulavacharu - Uppal</a></li>
                    <li><a href="#">Rayalaseema Ruchulu - LB Nagar</a></li>
                    <li><a href="#">Kakatiya Mess - Vanasthalipuram</a></li>
                    <li><a href="#">Nellore Venkateswara - Nagole</a></li>
                    <li><a href="#">Kritunga - ECIL</a></li>
                    <li><a href="#">Kamat Hotel - Habsiguda</a></li>
                    <li><a href="#">Sri Kanya Tiffins - Tarnaka</a></li>
                    <li><a href="#">Kalinga Restaurant - Ramanthapur</a></li>
                    <li><a href="#">Nanking - Secunderabad</a></li>
                    <li><a href="#">Kohinoor - Malkajgiri</a></li>
                </ul>
            </div>
            
            <div class="area-content" id="north-content">
                <h3>Best Restaurants & Street Food in North Hyderabad</h3>
                <ul class="area-list">
                    <li><a href="#">Kamat Hotel - Secunderabad</a></li>
                    <li><a href="#">Nanking - Secunderabad</a></li>
                    <li><a href="#">Paradise - Secunderabad</a></li>
                    <li><a href="#">Firdaus - Trimulgherry</a></li>
                    <li><a href="#">Kritunga - Alwal</a></li>
                    <li><a href="#">Taj Mahal Hotel - Secunderabad</a></li>
                    <li><a href="#">Kalinga Restaurant - Bowenpally</a></li>
                    <li><a href="#">Minerva Coffee Shop - Secunderabad</a></li>
                    <li><a href="#">Mouzzam - Trimulgherry</a></li>
                    <li><a href="#">Kohinoor - Malkajgiri</a></li>
                </ul>
            </div>
            
            <div class="area-content" id="south-content">
                <h3>Best Restaurants & Street Food in South Hyderabad</h3>
                <ul class="area-list">
                    <li><a href="#">Shah Ghouse - Tolichowki</a></li>
                    <li><a href="#">Pista House - Old City</a></li>
                    <li><a href="#">Shadab - Old City</a></li>
                    <li><a href="#">Bawarchi - RTC Cross Roads</a></li>
                    <li><a href="#">Café Bahar - Mehdipatnam</a></li>
                    <li><a href="#">Alhamdulillah - Tolichowki</a></li>
                    <li><a href="#">Shahran - Tolichowki</a></li>
                    <li><a href="#">Kamat Hotel - Mehdipatnam</a></li>
                    <li><a href="#">Nimrah Café - Charminar</a></li>
                    <li><a href="#">Grand Hotel - Abids</a></li>
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
            
            <div class="card-grid">
                <!-- Recipe Card 1 -->
                <div class="card recipe-card">
                    <div class="recipe-badge">30 mins</div>
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1589301760014-d929f3979dbc?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Hyderabadi Biryani">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Hyderabadi Dum Biryani</h3>
                        <div class="card-meta">
                            <span><i class="fas fa-utensils"></i> Main Course</span>
                            <span><i class="fas fa-fire"></i> Medium</span>
                        </div>
                        <p class="card-excerpt">The world-famous Hyderabadi biryani with layers of fragrant rice and perfectly spiced meat, cooked to perfection using the dum method.</p>
                        <a href="hyderabadi-biryani-recipe.html" class="btn">View Recipe</a>
                    </div>
                </div>
                
                <!-- Recipe Card 2 -->
                <div class="card recipe-card">
                    <div class="recipe-badge">2 hours</div>
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1601050690597-df0568f70950?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Haleem">
                    </div>
                    <div class
