# Project Responsive Web Design using Bootstrap
## Date:27.12.2024

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
    <title>Responsive Design</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .card img {
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="container py-5">
        <h1 class="mb-4 text-center">Sample Design</h1>
        <div class="row">
            <!-- Repeatable card structure -->
            <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                <div class="card shadow-sm">
                    <img src="https://via.placeholder.com/150" class="card-img-top" alt="Sample">
                    <div class="card-body">
                        <h5 class="card-title">Project Title</h5>
                        <p class="card-text text-muted">Short description here.</p>
                    </div>
                </div>
            </div>
            <!-- Duplicate this card for more items -->
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-27 223634.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
