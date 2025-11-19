# Project Responsive Web Design using Bootstrap
## Date:

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a href="#signup" class="btn btn-success ms-2">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
      <section class="text-center py-5 bg-secondary">
        <div class="container ">
            <h1 class="display-4 text-light">NATURE PHOTOGRAPHY PORTFOLIO</h1>
            <p class="lead text-light"></p>
        </div>
    </section>
    <section class="py-5 bg-dark">
        <div class="container">
            <h2 class="text-light text-center mb-4"></h2>
            <div class="row g-4">
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro1.jpeg"class="img-fluid rounded" alt="Nature 1" >
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro2.jpeg" class="img-fluid rounded" alt="Nature2">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro3.jpg" class="img-fluid rounded" alt="Nature 3">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro4.jpg" class="img-fluid rounded" alt="Nature 4">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro5.jpeg" class="img-fluid rounded" alt=" Nature5">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro6.jpg" class="img-fluid rounded" alt="Nature 6">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro9.jpeg" class="img-fluid rounded" alt="Nature 7">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="pro8.jpeg" class="img-fluid rounded" alt=" Nature8">
                </div>
                </div>
        </div>
    </section>
    
    <footer class="bg-dark text-light py-3">
        <div class="container text-center">
            <p>Designed and Developed by POOJA P</p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2025-05-21 225908.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
