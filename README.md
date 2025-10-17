# Project Responsive Web Design using Bootstrap
## Date:17/10/2025

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
    <title>Dheenadhaya.S.R - (25017597)</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-secondary">
        <div class="container">
            <a class="navbar-brand text-dark" href="#">Dribble Designs</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active text-dark" aria-current="page" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Team</a></li>
                    <li class="nav-item"><a class="btn btn-info ms-3" href="#">Job</a></li>
                    <li class="nav-item"><a class="btn btn-info ms-3" href="#">Sign in</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="text-center bg-primary text-white py-5">
        <div class="container">
            <h1 class="display-4">Discovering Creative Design</h1>
            <p class="lead">Showcase your designs and get inspired by others.</p>
            <a href="#" class="btn btn-info btn-lg me-2">Get Learn More</a>
            <a href="#" class="btn btn-info btn-lg">Sign up</a>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <h2 class="mb-4 text-center">Featured Shots</h2>
            <div class="row g-3 justify-content-center">
                
                <div class="col-12 text-center mb-4">
                    <div class="d-inline-block" style="width: 200px;">
                        <select class="form-select" aria-label="Sort">
                            <option selected>Popular</option>
                            <option>Recent</option>
                            <option>Following</option>
                        </select>
                    </div>
                </div>

                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/design1/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 1">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/branding2/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 2">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/uiux3/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 3">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/mobile4/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 4">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/web5/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 5">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/illustration6/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 6">
                    </div>
                </div>

                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/typography7/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 7">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/product8/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 8">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/flatdesign9/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 9">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/material10/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 10">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/abstract11/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 11">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/appdesign12/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 12">
                    </div>
                </div>

                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/minimalist13/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 13">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/darkmode14/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 14">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/logofolio15/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 15">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/geometric16/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 16">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/infographic17/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 17">
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 col-sm-6 col-12">
                    <div class="card">
                        <img src="https://picsum.photos/seed/3ddesign18/200/150" class="card-img-top object-fit-cover" style="height: 120px;" alt="Shot 18">
                    </div>
                </div>
                
            </div>
        </div>
    </section>
    
    <footer class="bg-danger text-white text-center py-3">
        <p class="mb-0">&copy; 2025 Developed by Dheenadhaya.S.R - (25017597)</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (46).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
