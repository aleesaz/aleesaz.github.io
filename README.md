<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nutrition & Health Blog</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Nutrition & Health Blog</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="blog.html">Blog</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Welcome to Our Nutrition & Health Blog!</h2>
            <p>Explore articles on diet, fitness, wellness, and more.</p>
        </div>
    </section>

    <section id="featured">
        <div class="container">
            <h2>Featured Articles</h2>
            <!-- Example articles -->
            <div class="article">
                <h3>Healthy Eating: A Beginner's Guide</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ac ante eros.</p>
                <a href="#">Read more</a>
            </div>
            <div class="article">
                <h3>Fitness Tips for Busy Professionals</h3>
                <p>Phasellus nec urna molestie, luctus neque sit amet, consectetur elit.</p>
                <a href="#">Read more</a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Nutrition & Health Blog. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nutrition & Health Blog - Blog</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Nutrition & Health Blog</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="blog.html">Blog</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="blog">
        <div class="container">
            <h2>Latest Articles</h2>
            <div class="article">
                <h3>Boost Your Energy Levels with These Foods</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ac ante eros.</p>
                <a href="#">Read more</a>
            </div>
            <div class="article">
                <h3>Yoga Poses for Stress Relief</h3>
                <p>Phasellus nec urna molestie, luctus neque sit amet, consectetur elit.</p>
                <a href="#">Read more</a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Nutrition & Health Blog. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* Reset and basic styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f0f0f0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

header h1 {
    margin: 0;
    padding: 0;
    font-size: 24px;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

#hero {
    background-color: #f7f7f7;
    padding: 50px 0;
    text-align: center;
}

#featured {
    padding: 50px 0;
}

.article {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    margin-bottom: 20px;
}

.article h3 {
    margin-top: 0;
}

.article p {
    color: #666;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}
