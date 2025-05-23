# Project Responsive Web Design using Bootstrap
## Date: 23-05-2025

NAME:AANANDHA KANNAN.S

REG NO:212224040003

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
  <title>Design Showcase</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f5f5f5;
    }
    .navbar {
      background-color: #333;
    }
    .navbar-brand, .nav-link, .navbar-text {
      color: #fff !important;
    }
    .card-img-top {
      height: 150px;
      object-fit: cover;
    }
    .designer-info {
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Style</a>
      <div class="collapse navbar-collapse justify-content-end">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Sign up</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Sign in</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container mt-4">
    <h2 class="mb-4">Shots</h2>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4">
      <!-- Static Cards -->
      <!-- Repeat 12 cards -->
      <!-- Card Template -->
      <div class="col">
        <div class="card">
          <img src="app1.jpg" class="card-img-top" alt="Design 1">
          <div class="card-body">
            <h5 class="card-title">CREATIVE APP INTERFACE</h5>
            <p class="designer-info">1204 views · 198 likes</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="app2.jpg" class="card-img-top" alt="Design 2">
          <div class="card-body">
            <h5 class="card-title">ECOMMERCE WEB DESIGNER</h5>
            <p class="designer-info">2044 views · 221 likes</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="appp3.jpg" class="card-img-top" alt="Design 3">
          <div class="card-body">
            <h5 class="card-title">FULL STACK DEVLOPER</h5>
            <p class="designer-info">1801 views · 142 likes</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="image19.jpg" class="" alt="Design 4">
          <div class="card-body">
            <h5 class="card-title">ENGLISH LEARNING PLATFORM</h5>
            <p class="designer-info">1922 views · 198 likes</p>
          </div>
        </div>
      </div>
    
        </div>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/74780e64-0656-40b5-86e4-dab6c29f9e3a)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
