<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simply Recipes</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="stylesheet" href="./fontawesome-free-6.2.0-web/fontawesome-free-6.2.0-web/css/all.css">
    <link rel="stylesheet" href="./css/styles2.css">
</head>
<body>
    <!-- nav  -->
    <nav class="navbar">
        <div class="nav-center">
            <!-- header  -->
            <div class="nav-header">
                <a href="index.html" class="nav-logo">
                    <img src="./images/logo.png" alt="simply recipes">
                </a>
                <button type="button" class="btn nav-btn">
                <i class="fas fa-align-justify"></i>
                </button>
            </div>
            <!-- link  -->
            <div class="nav-links show-links">
                <a href="index.html" class="nav-link">Home</a>
                <a href="about.html" class="nav-link">About</a>
                <a href="tags.html" class="nav-link">Tags</a>
                <a href="recipes.html" class="nav-link">Recipes</a>
                <div class="nav-link contact-link">
                    <a href="contact.html" class="btn">Contact</a>
                </div>
            </div>
        </div>
    </nav>
    <!-- end of nav  -->

    <!-- main  -->
    <main class="page">

        <!-- header  -->
        <header class="hero">
            <div class="hero-container">
                <div class="hero-text">
                    <h1>Simply Recipes</h1>
                    <h4>No fluff, just recipes</h4>
                </div>
            </div>
        </header>
        <!-- end of header -->

        <!-- recipes container  -->
        <section class="recipes-container">
            <!-- tags container  -->
            <div class="tags-container">
                <h4>Recipes</h4>
                <div class="tags-list">
                    <a href="tag-template.html">Breakfast (2)</a>
                    <a href="tag-template.html">Lunch (3)</a>
                    <a href="tag-template.html">Dinner (1)</a>
                </div>
            </div>
            <!-- end of tags container  -->

            <!-- recipes list  -->
            <div class="recipes-list">
                <!-- single recipe  -->
                <a href="single-recipe.html" class="recipe">
                    <img src="./images/recipes/breakfast 1.jpeg" alt="breakfast" class="img recipe-img"/>
                    <h5>Pancakes</h5>
                    <p>Prep : 15min | Cook : 5min</p>
                </a>

                <a href="single-recipe.html" class="recipe">
                    <img src="./images/recipes/breakfast 2.webp" alt="breakfast" class="img recipe-img" />
                    <h5>Eggs Over Toast</h5>
                    <p>Prep : 10min | Cook : 7min</p>
                </a>
                
                <a href="single-recipe.html" class="recipe">
                    <img src="./images/recipes/lunch 1.webp" alt="lunch" class="img recipe-img" />
                    <h5>Spaghetti</h5>
                    <p>Prep : 15min | Cook : 10min</p>
                </a>

                <a href="single-recipe.html" class="recipe">
                    <img src="./images/recipes/dinner 1.jpeg" alt="dinner" class="img recipe-img" />
                    <h5>full course meal</h5>
                    <p>Prep : 15min | Cook : 20min</p>
                </a>
                <!-- end of single recipe  -->
            </div>
            <!-- end of recipes list -->
        </section>
        <!-- end of recipes container  -->

    </main>
    <!-- end of main  --> 

    <!-- footer  -->
    <footer class="page-footer">
        <p>&copy; <span id="date"></span> 
        <span class="footer-logo">SimplyRecipes</span>
        </p>
    </footer>

    <script src="./js/app.js"></script>

</body>
</html>
