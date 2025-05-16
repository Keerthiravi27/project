# Project Responsive Web Design using Bootstrap
# Date: 15/05/2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background-color: #f8f9fa;
      padding: 100px 20px;
      text-align: center;
    }
    .shot-img {
      border-radius: 10px;
      width: 100%;
      height: auto;
    }
    footer {
      background-color: #212529;
      color: rgb(247, 243, 243);
      text-align: center;
      padding: 20px 0;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
          <li class="nav-item"><a class="btn btn-primary ms-2" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1 class="display-4 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead mt-3 mb-4">Dribbble is the leading destination to find & showcase creative work and home to the world’s best design professionals.</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Featured Shots -->
  <section class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4 text-center fw-bold">Explore Popular Shots</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-16 133535.png" alt="Shot 1" class="shot-img shadow-sm">
        </div>
        
          <div class="col-md-4">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-16 133634.png" alt="Shot 2" class="shot-img shadow-sm">
        </div>
        <div class="col-md-4">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-16 134104.png" alt="Shot 3" class="shot-img shadow-sm">
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p class="mb-0">© 2025 Designed by Keerthana Ravichandran</p>
    </div>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot 2025-05-16 135530](https://github.com/user-attachments/assets/5caa7671-270f-4426-aedd-96ab90317268)
![Screenshot 2025-05-16 135542](https://github.com/user-attachments/assets/6eab0200-6e02-481d-9d89-1315125270e2)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
