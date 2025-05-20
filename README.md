# Project Responsive Web Design using Bootstrap


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
<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Top Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">Dribbble Clone</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Shots</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Designers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Community</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Jobs</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign Up</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign In</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Banner Section -->
<header class="bg-light text-center py-5">
    <div class="container">
        <h1 class="display-4">What are you working on?</h1>
        <p class="lead">Dribbble is a show-and-tell platform for designers. Discover, connect, and share your creations.</p>
        <a href="#gallery" class="btn btn-primary btn-lg">Explore Now</a>
        <a href="#" class="btn btn-outline-secondary btn-lg">Learn More</a>
    </div>
</header>

<!-- Gallery Section -->
<section id="gallery" class="bg-light py-5">
    <div class="container">
        <h2 class="text-center mb-4">Popular Shots</h2>
        <div class="row">

            <div class="col-md-3 col-sm-6 mb-4">
                <img src="61.png" class="img-fluid rounded" alt="Design 2">
                <p class="mt-2 text-center">Balkan Brothers</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="62.png" class="img-fluid rounded" alt="Design 3">
                <p class="mt-2 text-center">Jan Losert</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="63.png" class="img-fluid rounded" alt="Design 4">
                <p class="mt-2 text-center">Mattias Johansson</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="64.png" class="img-fluid rounded" alt="Design 5">
                <p class="mt-2 text-center">Ruslan Siiz</p>
            </div>
          

        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
    <div class="container">
        <p>Designed by Prathikshaa.S</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-20 131450](https://github.com/user-attachments/assets/b8544080-3a59-4a95-b9e9-20d52a119f71)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
