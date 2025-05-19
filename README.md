<html lang="en-IN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Best food blog in Hyderabad featuring restaurant reviews, street food guides, and authentic Hyderabadi recipes">
    <meta name="keywords" content="Hyderabad food, Hyderabadi biryani, best restaurants Hyderabad, street food Hyderabad, food blog India">
    <meta name="author" content="Hyderabad Foodie">
    <meta name="geo.region" content="IN-TG">
    <meta name="geo.placename" content="Hyderabad">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://www.hyderabadfoodblog.com">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="Hyderabad Food Blog | Best Restaurants & Street Food Guide">
    <meta property="og:description" content="Discover the best food in Hyderabad - from luxury dining to hidden street food gems">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.hyderabadfoodblog.com">
    <meta property="og:image" content="https://www.hyderabadfoodblog.com/images/og-image.jpg">
    <meta property="og:site_name" content="Hyderabad Food Blog">
    
    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Hyderabad Food Blog | Best Restaurants & Street Food Guide">
    <meta name="twitter:description" content="Discover the best food in Hyderabad - from luxury dining to hidden street food gems">
    <meta name="twitter:image" content="https://www.hyderabadfoodblog.com/images/twitter-card.jpg">
    
    <!-- Favicon -->
    <link rel="icon" href="/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    
    <!-- Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite",
      "name": "Hyderabad Food Blog",
      "url": "https://www.hyderabadfoodblog.com",
      "potentialAction": {
        "@type": "SearchAction",
        "target": "https://www.hyderabadfoodblog.com/search?q={search_term_string}",
        "query-input": "required name=search_term_string"
      }
    }
    </script>
    
    <title>Hyderabad Food Blog | Best Restaurants & Street Food Guide</title>
    
    <!-- Preload critical resources -->
    <link rel="preload" href="css/styles.css" as="style">
    <link rel="preload" href="js/main.js" as="script">
    
    <!-- CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #FF6B6B;
            --secondary-color: #FFA07A;
            --dark-color: #333;
            --light-color: #f8f9fa;
            --success-color: #28a745;
            --warning-color: #ffc107;
            --danger-color: #dc3545;
            --max-width: 1200px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--dark-color);
            background-color: #f5f5f5;
        }
        
        a {
            text-decoration: none;
            color: var(--primary-color);
            transition: all 0.3s ease;
        }
        
        a:hover {
            color: var(--secondary-color);
        }
        
        img {
            max-width: 100%;
            height: auto;
        }
        
        .container {
            width: 100%;
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 100;
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
            color: var(--secondary-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            font-weight: 600;
            color: var(--dark-color);
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--dark-color);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1585937421612-70a008356fbe?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            margin-bottom: 30px;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: var(--secondary-color);
            color: white;
            transform: translateY(-3px);
        }
        
        /* Tab Navigation */
        .tab-navigation {
            display: flex;
            border-bottom: 1px solid #ddd;
            margin-bottom: 30px;
        }
        
        .tab-btn {
            padding: 10px 20px;
            background: none;
            border: none;
            cursor: pointer;
            font-weight: 600;
            color: #666;
            position: relative;
        }
        
        .tab-btn.active {
            color: var(--primary-color);
        }
        
        .tab-btn.active::after {
            content: '';
            position: absolute;
            bottom: -1px;
            left: 0;
            width: 100%;
            height: 2px;
            background: var(--primary-color);
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        /* Restaurant/Street Food/Recipe Cards */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .card-img {
            height: 200px;
            width: 100%;
            object-fit: cover;
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
            align-items: center;
            margin-bottom: 15px;
            color: #666;
            font-size: 0.9rem;
        }
        
        .card-meta span {
            margin-right: 15px;
        }
        
        .card-meta i {
            margin-right: 5px;
            color: var(--primary-color);
        }
        
        .card-rating {
            color: var(--warning-color);
            font-weight: 600;
        }
        
        .card-price {
            font-weight: 600;
            color: var(--success-color);
        }
        
        .card-excerpt {
            margin-bottom: 15px;
            font-size: 0.95rem;
        }
        
        /* Recipe Specific Styles */
        .recipe-meta {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 15px;
        }
        
        .recipe-meta-item {
            display: flex;
            align-items: center;
            margin-right: 20px;
            margin-bottom: 10px;
            font-size: 0.9rem;
        }
        
        .recipe-meta-item i {
            margin-right: 5px;
            color: var(--primary-color);
        }
        
        /* Main Content */
        .main {
            display: flex;
            flex-wrap: wrap;
            margin: 30px 0;
        }
        
        .content {
            flex: 2;
            min-width: 300px;
            padding-right: 30px;
        }
        
        .sidebar {
            flex: 1;
            min-width: 250px;
        }
        
        /* Blog Posts */
        .blog-post {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
            overflow: hidden;
        }
        
        .post-header {
            position: relative;
        }
        
        .post-category {
            position: absolute;
            top: 15px;
            left: 15px;
            background: var(--primary-color);
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.8rem;
            font-weight: 600;
        }
        
        .post-content {
            padding: 20px;
        }
        
        .post-title {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        
        .post-meta {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            color: #666;
            font-size: 0.9rem;
        }
        
        .post-meta span {
            margin-right: 15px;
        }
        
        .post-meta i {
            margin-right: 5px;
        }
        
        .post-excerpt {
            margin-bottom: 20px;
        }
        
        .read-more {
            display: inline-block;
            font-weight: 600;
        }
        
        /* Sidebar */
        .sidebar-widget {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            padding: 20px;
            margin-bottom: 30px;
        }
        
        .widget-title {
            font-size: 1.2rem;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--light-color);
            color: var(--primary-color);
        }
        
        .popular-posts {
            list-style: none;
        }
        
        .popular-post {
            display: flex;
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }
        
        .popular-post:last-child {
            margin-bottom: 0;
            padding-bottom: 0;
            border-bottom: none;
        }
        
        .popular-post-img {
            width: 80px;
            height: 60px;
            object-fit: cover;
            border-radius: 5px;
            margin-right: 15px;
        }
        
        .popular-post-title {
            font-size: 0.9rem;
            font-weight: 600;
        }
        
        .popular-post-date {
            font-size: 0.8rem;
            color: #666;
        }
        
        .categories-list {
            list-style: none;
        }
        
        .categories-list li {
            margin-bottom: 10px;
            padding-bottom: 10px;
            border-bottom: 1px solid #eee;
        }
        
        .categories-list li:last-child {
            margin-bottom: 0;
            padding-bottom: 0;
            border-bottom: none;
        }
        
        .categories-list a {
            display: flex;
            justify-content: space-between;
            color: var(--dark-color);
        }
        
        .categories-list a:hover {
            color: var(--primary-color);
        }
        
        .categories-list span {
            background: var(--light-color);
            padding: 2px 8px;
            border-radius: 10px;
            font-size: 0.8rem;
        }
        
        /* Newsletter */
        .newsletter-form {
            margin-top: 20px;
        }
        
        .newsletter-form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        
        .newsletter-form button {
            width: 100%;
            padding: 10px;
            background: var(--primary-color);
            color: white;
            border: none;
            border-radius: 5px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .newsletter-form button:hover {
            background: var(--secondary-color);
        }
        
        /* Ad Spaces */
        .ad-space {
            background: #f0f0f0;
            border: 1px dashed #ccc;
            padding: 20px;
            text-align: center;
            margin-bottom: 30px;
            border-radius: 5px;
        }
        
        .ad-space p {
            color: #666;
            margin-bottom: 10px;
        }
        
        .ad-space-large {
            padding: 30px;
            margin: 40px 0;
        }
        
        /* Comments Section */
        .comments-section {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            padding: 20px;
            margin-top: 30px;
        }
        
        .comments-title {
            font-size: 1.3rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .comment {
            display: flex;
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }
        
        .comment:last-child {
            margin-bottom: 0;
            padding-bottom: 0;
            border-bottom: none;
        }
        
        .comment-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 15px;
            object-fit: cover;
        }
        
        .comment-content {
            flex: 1;
        }
        
        .comment-author {
            font-weight: 600;
            margin-bottom: 5px;
        }
        
        .comment-date {
            font-size: 0.8rem;
            color: #666;
            margin-bottom: 10px;
        }
        
        .comment-text {
            font-size: 0.95rem;
        }
        
        .comment-form {
            margin-top: 30px;
        }
        
        .form-group {
            margin-bottom: 15px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
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
        
        /* Footer */
        footer {
            background: var(--dark-color);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        
        .footer-widget {
            flex: 1;
            min-width: 250px;
            margin-bottom: 30px;
            padding: 0 15px;
        }
        
        .footer-widget h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .footer-widget p {
            margin-bottom: 15px;
            font-size: 0.9rem;
            color: #bbb;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links a {
            color: #bbb;
            transition: all 0.3s ease;
        }
        
        .footer-links a:hover {
            color: var(--primary-color);
            padding-left: 5px;
        }
        
        .social-links {
            display: flex;
            list-style: none;
        }
        
        .social-links li {
            margin-right: 15px;
        }
        
        .social-links a {
            display: inline-block;
            width: 40px;
            height: 40px;
            background: #444;
            color: white;
            border-radius: 50%;
            text-align: center;
            line-height: 40px;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            margin-top: 20px;
            border-top: 1px solid #444;
            font-size: 0.9rem;
            color: #bbb;
        }
        
        /* Pagination */
        .pagination {
            display: flex;
            justify-content: center;
            margin: 30px 0;
        }
        
        .pagination a {
            display: inline-block;
            padding: 8px 15px;
            margin: 0 5px;
            border: 1px solid #ddd;
            border-radius: 5px;
            color: var(--dark-color);
        }
        
        .pagination a.active,
        .pagination a:hover {
            background: var(--primary-color);
            color: white;
            border-color: var(--primary-color);
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
                flex-direction: column;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .mobile-menu-btn {
                display: block;
                position: absolute;
                top: 20px;
                right: 20px;
            }
            
            .content {
                padding-right: 0;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .footer-widget {
                flex: 100%;
                text-align: center;
            }
            
            .social-links {
                justify-content: center;
            }
            
            .tab-navigation {
                overflow-x: auto;
                white-space: nowrap;
                padding-bottom: 5px;
            }
            
            .tab-btn {
                padding: 10px 15px;
            }
        }
        
        /* Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .animated {
            animation: fadeIn 0.5s ease forwards;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <a href="index.html" class="logo">Hyderabad<span>Foodie</span></a>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            
            <nav id="mainNav">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="restaurants.html" class="active">Restaurants</a></li>
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
        <div class="hero-content">
            <h1>Discover the Best Food in Hyderabad</h1>
            <p>From luxury dining to hidden street food gems - your ultimate guide to Hyderabad's vibrant food scene</p>
            <a href="#featured" class="btn">Explore Now</a>
        </div>
    </section>
    
    <!-- Main Content -->
    <main class="container main">
        <!-- Content Area -->
        <div class="content">
            <!-- Tab Navigation -->
            <div class="tab-navigation">
                <button class="tab-btn active" data-tab="restaurants">Luxury Restaurants</button>
                <button class="tab-btn" data-tab="street-food">Street Food</button>
                <button class="tab-btn" data-tab="recipes">Recipes</button>
            </div>
            
            <!-- Restaurants Tab Content -->
            <div id="restaurants" class="tab-content active">
                <h2>Top Luxury Restaurants in Hyderabad</h2>
                <p>Experience fine dining at its best with our curated list of Hyderabad's most luxurious restaurants</p>
                
                <!-- Ad Space (Top of Content) -->
                <div class="ad-space">
                    <p>Advertisement</p>
                    <!-- Google AdSense Ad Unit -->
                    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
                    <!-- Food Blog Top Banner -->
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
                
                <div class="card-grid">
                    <!-- Restaurant 1 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Taj Falaknuma Palace" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Taj Falaknuma Palace</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.8</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Falaknuma</span>
                            </div>
                            <p class="card-excerpt">Dine like royalty in this stunning palace with authentic Nizami cuisine and impeccable service.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Restaurant 2 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Ohri's Jiva Imperia" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Ohri's Jiva Imperia</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.6</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Jubilee Hills</span>
                            </div>
                            <p class="card-excerpt">Multi-cuisine fine dining with live music and an extensive wine selection.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Restaurant 3 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1550966871-3ed3cdb5ed0c?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Kebabs & Kurries" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Kebabs & Kurries</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.7</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> ITC Kohenur</span>
                            </div>
                            <p class="card-excerpt">Authentic North Indian and Hyderabadi cuisine with a modern twist.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Restaurant 4 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1537047902294-62a40c20a6ae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Ministry of Barbeque" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Ministry of Barbeque</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.5</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Gachibowli</span>
                            </div>
                            <p class="card-excerpt">Premium buffet with live grills and unlimited barbecue options.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Restaurant 5 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="The Waterfront" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">The Waterfront</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.4</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Necklace Road</span>
                            </div>
                            <p class="card-excerpt">Romantic fine dining with stunning views of Hussain Sagar lake.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Restaurant 6 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Flechazo" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Flechazo</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.6</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹₹₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Banjara Hills</span>
                            </div>
                            <p class="card-excerpt">Premium North Indian cuisine with live music and elegant ambiance.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- Ad Space (Middle of Content) -->
                <div class="ad-space ad-space-large">
                    <p>Advertisement</p>
                    <!-- Google AdSense Ad Unit -->
                    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
                    <!-- Food Blog Middle Rectangle -->
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
            
            <!-- Street Food Tab Content -->
            <div id="street-food" class="tab-content">
                <h2>Best Street Food Spots in Hyderabad</h2>
                <p>Explore the vibrant street food culture of Hyderabad with these must-visit spots</p>
                
                <!-- Ad Space (Top of Content) -->
                <div class="ad-space">
                    <p>Advertisement</p>
                    <!-- Google AdSense Ad Unit -->
                    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
                    <!-- Food Blog Top Banner -->
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
                
                <div class="card-grid">
                    <!-- Street Food 1 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Shah Ghouse Cafe" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Shah Ghouse Cafe</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.5</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Toli Chowki</span>
                            </div>
                            <p class="card-excerpt">Famous for their haleem and biryani, open 24/7 with amazing flavors.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Street Food 2 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Nayab Hotel" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Nayab Hotel</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.3</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Old City</span>
                            </div>
                            <p class="card-excerpt">Legendary haleem during Ramadan and amazing kebabs year-round.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Street Food 3 -->
                    <div class="card animated">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Pista House" class="card-img">
                        <div class="card-content">
                            <h3 class="card-title">Pista House</h3>
                            <div class="card-meta">
                                <span><i class="fas fa-star"></i> <span class="card-rating">4.4</span>/5</span>
                                <span><i class="fas fa-rupee-sign"></i> <span class="card-price">₹</span></span>
                                <span><i class="fas fa-map-marker-alt"></i> Nampally</span>
                            </div>
                            <p class="card-excerpt">The most famous haleem in Hyderabad with multiple outlets.</p>
                            <a href="#" class="read-more">Read Review <i class="fas fa-arrow-right"></i></a>
                        </div>
                    </div>
                    
                    <!-- Street Food 4 -->
                    <div class="card animated">
                        <img src="https
