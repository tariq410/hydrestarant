<!DOCTYPE html>
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
            <!-- Featured Post -->
            <article class="blog-post animated" id="featured">
                <div class="post-header">
                    <img src="https://images.unsplash.com/photo-1589301760014-d929f3979dbc?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Hyderabadi Biryani">
                    <span class="post-category">Featured</span>
                </div>
                <div class="post-content">
                    <h2 class="post-title">The Ultimate Guide to Hyderabadi Biryani: Top 10 Places to Try</h2>
                    <div class="post-meta">
                        <span><i class="far fa-user"></i> By Foodie Admin</span>
                        <span><i class="far fa-calendar-alt"></i> June 15, 2023</span>
                        <span><i class="far fa-comments"></i> 24 Comments</span>
                    </div>
                    <p class="post-excerpt">Hyderabadi Biryani is not just a dish, it's an emotion for the people of Hyderabad. After tasting over 50 different biryanis across the city, we've curated this list of the absolute best places to experience authentic Hyderabadi Biryani...</p>
                    <a href="hyderabadi-biryani-guide.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
            </article>
            
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
            
            <!-- Recent Posts -->
            <article class="blog-post animated">
                <div class="post-header">
                    <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Street Food in Hyderabad">
                    <span class="post-category">Street Food</span>
                </div>
                <div class="post-content">
                    <h2 class="post-title">Hidden Street Food Gems in Old Hyderabad</h2>
                    <div class="post-meta">
                        <span><i class="far fa-user"></i> By Street Food Explorer</span>
                        <span><i class="far fa-calendar-alt"></i> June 10, 2023</span>
                        <span><i class="far fa-comments"></i> 18 Comments</span>
                    </div>
                    <p class="post-excerpt">Old Hyderabad is a treasure trove of culinary delights waiting to be discovered. From the legendary Irani chai to the crispy Osmania biscuits, join us as we explore 15 must-try street food spots that even many locals don't know about...</p>
                    <a href="old-hyderabad-street-food.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
            </article>
            
            <article class="blog-post animated">
                <div class="post-header">
                    <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Fine Dining in Hyderabad">
                    <span class="post-category">Fine Dining</span>
                </div>
                <div class="post-content">
                    <h2 class="post-title">10 Best Fine Dining Restaurants in Hyderabad for a Special Night Out</h2>
                    <div class="post-meta">
                        <span><i class="far fa-user"></i> By Gourmet Guru</span>
                        <span><i class="far fa-calendar-alt"></i> June 5, 2023</span>
                        <span><i class="far fa-comments"></i> 12 Comments</span>
                    </div>
                    <p class="post-excerpt">Hyderabad's fine dining scene has exploded in recent years with world-class restaurants offering everything from authentic Indian royal cuisine to innovative global fusion. Whether you're celebrating an anniversary or just want to treat yourself, these are our top picks for an unforgettable dining experience...</p>
                    <a href="fine-dining-hyderabad.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
            </article>
            
            <!-- Comments Section -->
            <section class="comments-section animated">
                <h3 class="comments-title">Leave a Comment</h3>
                
                <div class="comment-form">
                    <form id="commentForm">
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="comment">Comment</label>
                            <textarea id="comment" name="comment" required></textarea>
                        </div>
                        <button type="submit" class="btn">Post Comment</button>
                    </form>
                </div>
                
                <h3 class="comments-title">Recent Comments</h3>
                
                <div class="comment">
                    <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="User" class="comment-avatar">
                    <div class="comment-content">
                        <h4 class="comment-author">Priya Sharma</h4>
                        <span class="comment-date">June 14, 2023 at 3:45 PM</span>
                        <p class="comment-text">Great article! I've tried 7 out of the 10 biryani places mentioned and completely agree with your rankings. Paradise is overrated compared to some of these hidden gems.</p>
                    </div>
                </div>
                
                <div class="comment">
                    <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="User" class="comment-avatar">
                    <div class="comment-content">
                        <h4 class="comment-author">Rahul Mehta</h4>
                        <span class="comment-date">June 12, 2023 at 10:20 AM</span>
                        <p class="comment-text">You missed the amazing biryani at Cafe Bahar! It's my personal favorite. Maybe include it in your next update?</p>
                    </div>
                </div>
            </section>
            
            <!-- Pagination -->
            <div class="pagination">
                <a href="#" class="active">1</a>
                <a href="#">2</a>
                <a href="#">3</a>
                <a href="#">4</a>
                <a href="#"><i class="fas fa-chevron-right"></i></a>
            </div>
        </div>
        
        <!-- Sidebar -->
        <aside class="sidebar">
            <!-- About Widget -->
            <div class="sidebar-widget animated">
                <h3 class="widget-title">About Hyderabad Foodie</h3>
                <img src="https://images.unsplash.com/photo-1547592180-85f173990554?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="About Us" style="border-radius: 5px; margin-bottom: 15px;">
                <p>Hyderabad Foodie is dedicated to exploring and sharing the best food experiences in Hyderabad. From street food to fine dining, we're passionate about everything this city has to offer.</p>
            </div>
            
            <!-- Ad Space (Sidebar Top) -->
            <div class="ad-space">
                <p>Advertisement</p>
                <!-- Google AdSense Ad Unit -->
                <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
                <!-- Sidebar Square Ad -->
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
            
            <!-- Popular Posts -->
            <div class="sidebar-widget animated">
                <h3 class="widget-title">Popular Posts</h3>
                <ul class="popular-posts">
                    <li class="popular-post">
                        <img src="https://images.unsplash.com/photo-1599043513900-ed6fe01d3833?ixlib=rb-1.2.1&auto=format&fit=crop&w=150&q=80" alt="Popular Post" class="popular-post-img">
                        <div>
                            <a href="#" class="popular-post-title">Best Cafés in Hyderabad for Coffee Lovers</a>
                            <div class="popular-post-date">May 28, 2023</div>
                        </div>
                    </li>
                    <li class="popular-post">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?ixlib=rb-1.2.1&auto=format&fit=crop&w=150&q=80" alt="Popular Post" class="popular-post-img">
                        <div>
                            <a href="#" class="popular-post-title">10 Must-Try Street Foods Under ₹100</a>
                            <div class="popular-post-date">May 20, 2023</div>
                        </div>
                    </li>
                    <li class="popular-post">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=150&q=80" alt="Popular Post" class="popular-post-img">
                        <div>
                            <a href="#" class="popular-post-title">Rooftop Restaurants with Best City Views</a>
                            <div class="popular-post-date">May 15, 2023</div>
                        </div>
                    </li>
                    <li class="popular-post">
                        <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?ixlib=rb-1.2.1&auto=format&fit=crop&w=150&q=80" alt="Popular Post" class="popular-post-img">
                        <div>
                            <a href="#" class="popular-post-title">Authentic Hyderabadi Haleem: Where to Find It</a>
                            <div class="popular-post-date">May 10, 2023</div>
                        </div>
                    </li>
                </ul>
            </div>
            
            <!-- Categories -->
            <div class="sidebar-widget animated">
                <h3 class="widget-title">Categories</h3>
                <ul class="categories-list">
                    <li><a href="#">Biryani Specials <span>15</span></a></li>
                    <li><a href="#">Street Food <span>28</span></a></li>
                    <li><a href="#">Fine Dining <span>12</span></a></li>
                    <li><a href="#">Cafés & Bakeries <span>18</span></a></li>
                    <li><a href="#">Hyderabadi Recipes <span>24</span></a></li>
                    <li><a href="#">Food Events <span>7</span></a></li>
                </ul>
            </div>
            
            <!-- Newsletter -->
            <div class="sidebar-widget animated">
                <h3 class="widget-title">Newsletter</h3>
                <p>Subscribe to get weekly updates on the best food spots in Hyderabad!</p>
                <form class="newsletter-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <button type="submit">Subscribe</button>
                </form>
            </div>
            
            <!-- Ad Space (Sidebar Bottom) -->
            <div class="ad-space">
                <p>Advertisement</p>
                <!-- Google AdSense Ad Unit -->
                <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
                <!-- Sidebar Vertical Ad -->
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
        </aside>
    </main>
    
    <!-- Footer -->
    <footer>
        <div class="container footer-container">
            <div class="footer-widget">
                <h3>About Hyderabad Foodie</h3>
                <p>We're passionate about Hyderabad's diverse food culture and committed to bringing you the most authentic and delicious experiences.</p>
                <div class="social-links">
                    <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                    <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                    <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                    <li><a href="#"><i class="fab fa-pinterest"></i></a></li>
                </div>
            </div>
            
            <div class="footer-widget">
                <h3>Quick Links</h3>
                <ul class="footer-links">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About Us</a></li>
                    <li><a href="restaurants.html">Restaurant Guides</a></li>
                    <li><a href="street-food.html">Street Food Guides</a></li>
                    <li><a href="recipes.html">Recipes</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </div>
            
            <div class="footer-widget">
                <h3>Food Categories</h3>
                <ul class="footer-links">
                    <li><a href="#">Biryani</a></li>
                    <li><a href="#">Haleem</a></li>
                    <li><a href="#">Irani Chai</a></li>
                    <li><a href="#">Kebabs</a></li>
                    <li><a href="#">Desserts</a></li>
                    <li><a href="#">Vegetarian</a></li>
                </ul>
            </div>
            
            <div class="footer-widget">
                <h3>Contact Info</h3>
                <p><i class="fas fa-map-marker-alt"></i> Hyderabad, Telangana, India</p>
                <p><i class="fas fa-envelope"></i> contact@hyderabadfoodie.com</p>
                <p><i class="fas fa-phone"></i> +91 98765 43210</p>
            </div>
        </div>
        
        <div class="copyright">
            <p>&copy; 2023 Hyderabad Foodie. All Rights Reserved.</p>
        </div>
    </footer>
    
    <!-- JavaScript -->
    <script>
        // Mobile Menu Toggle
        document.getElementById('mobileMenuBtn').addEventListener('click', function() {
            const nav = document.getElementById('mainNav');
            nav.style.display = nav.style.display === 'block' ? 'none' : 'block';
        });
        
        // Comment Form Submission
        document.getElementById('commentForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const comment = document.getElementById('comment').value;
            
            // Create new comment element
            const commentsSection = document.querySelector('.comments-section');
            const newComment = document.createElement('div');
            newComment.className = 'comment';
            newComment.innerHTML = `
                <img src="https://ui-avatars.com/api/?name=${encodeURIComponent(name)}&background=random" alt="User" class="comment-avatar">
                <div class="comment-content">
                    <h4 class="comment-author">${name}</h4>
                    <span class="comment-date">Just now</span>
                    <p class="comment-text">${comment}</p>
                </div>
            `;
            
            // Insert new comment before the comment form
            commentsSection.insertBefore(newComment, document.querySelector('.comment-form'));
            
            // Reset form
            this.reset();
            
            // Show success message
            alert('Thank you for your comment!');
        });
        
        // Newsletter Form Submission
        document.querySelector('.newsletter-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for subscribing to our newsletter!');
            this.reset();
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 100,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Lazy loading for images
        document.addEventListener('DOMContentLoaded', function() {
            const lazyImages = [].slice.call(document.querySelectorAll('img.lazy'));
            
            if ('IntersectionObserver' in window) {
                let lazyImageObserver = new IntersectionObserver(function(entries, observer) {
                    entries.forEach(function(entry) {
                        if (entry.isIntersecting) {
                            let lazyImage = entry.target;
                            lazyImage.src = lazyImage.dataset.src;
                            lazyImage.classList.remove('lazy');
                            lazyImageObserver.unobserve(lazyImage);
                        }
                    });
                });
                
                lazyImages.forEach(function(lazyImage) {
                    lazyImageObserver.observe(lazyImage);
                });
            }
        });
        
        // Add animation class to elements when they come into view
        const animateOnScroll = function() {
            const elements = document.querySelectorAll('.blog-post, .sidebar-widget');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.3;
                
                if (elementPosition < screenPosition) {
                    element.classList.add('animated');
                }
            });
        };
        
        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
    </script>
    
    <!-- Schema Markup for Breadcrumb -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "BreadcrumbList",
      "itemListElement": [{
        "@type": "ListItem",
        "position": 1,
        "name": "Home",
        "item": "https://www.hyderabadfoodblog.com"
      },{
        "@type": "ListItem",
        "position": 2,
        "name": "Blog",
        "item": "https://www.hyderabadfoodblog.com/blog"
      }]
    }
    </script>
</body>
</html>
