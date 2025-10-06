# Project Responsive Web Design using Bootstrap
# Date:06/10/2025
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



html

          <!DOCTYPE html>
          
          <html lang="en">
          <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Dribbble Clone</title>
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
            <style>
              body {
                font-family: 'Poppins', sans-serif;
                background-color: #f8f9fa;
              }
          
          ```
          /* Navbar */
          .navbar {
            background-color: #ea4c89;
          }
          
          .navbar-brand, .nav-link {
            color: black !important;
          }
          
          .nav-link:hover {
            text-decoration: underline;
          }
          
          /* Hero Section */
          .hero {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(120deg, #ea4c89, #f28cb6);
            color: white;
          }
          
          .hero h1 {
            font-weight: 700;
            margin-bottom: 20px;
          }
          
          .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
          }
          
          /* Shots Grid */
          .shot-card {
            border-radius: 15px;
            overflow: hidden;
            background-color: white;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
          }
          
          .shot-card:hover {
            transform: translateY(-5px);
          }
          
          .shot-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
          }
          
          .shot-card .card-body {
            padding: 15px;
          }
          
          .shot-card h5 {
            font-size: 1.1rem;
            color: #ea4c89;
            margin-bottom: 8px;
          }
          
          /* Footer */
          footer {
            background-color: #212529;
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-top: 50px;
          }
          ```
          
            </style>
          </head>
          <body>
          
            <!-- Navbar -->
          
            <nav class="navbar navbar-expand-lg">
              <div class="container">
                <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
                <button class="navbar-toggler bg-light" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navMenu">
                  <ul class="navbar-nav">
                    <li class="nav-item"><a href="#" class="nav-link">Inspiration</a></li>
                    <li class="nav-item"><a href="#" class="nav-link">Find Work</a></li>
                    <li class="nav-item"><a href="#" class="nav-link">Learn Design</a></li>
                    <li class="nav-item"><a href="#" class="nav-link" data-bs-toggle="modal" data-bs-target="#signinModal">Sign In</a></li>
                    <li class="nav-item"><a href="#" class="btn btn-light text-dark ms-2" data-bs-toggle="modal" data-bs-target="#signupModal">Sign Up</a></li>
                  </ul>
                </div>
              </div>
            </nav>
          
            <!-- Hero -->
          
            <section class="hero">
              <h1>Discover the world’s top designers & creatives</h1>
              <p>Dribbble is the leading destination to find & showcase creative work.</p>
              <button class="btn btn-light text-dark px-4 py-2">Explore Shots</button>
            </section>
          
            <!-- Featured Shots -->
          
            <section class="container mt-5">
              <h2 class="text-center mb-4">Featured Shots</h2>
              <div class="row g-4">
          
          ```
            <div class="col-md-3 col-sm-6">
              <div class="shot-card">
                <img src="https://picsum.photos/300/200?1" alt="">
                <div class="card-body">
                  <h5>Minimal Dashboard</h5>
                  <p>UI/UX Design</p>
                </div>
              </div>
            </div>
          
            <div class="col-md-3 col-sm-6">
              <div class="shot-card">
                <img src="https://picsum.photos/300/200?2" alt="">
                <div class="card-body">
                  <h5>Mobile App Concept</h5>
                  <p>App Interface</p>
                </div>
              </div>
            </div>
          
            <div class="col-md-3 col-sm-6">
              <div class="shot-card">
                <img src="https://picsum.photos/300/200?3" alt="">
                <div class="card-body">
                  <h5>Brand Logo Design</h5>
                  <p>Brand Identity</p>
                </div>
              </div>
            </div>
          
            <div class="col-md-3 col-sm-6">
              <div class="shot-card">
                <img src="https://picsum.photos/300/200?4" alt="">
                <div class="card-body">
                  <h5>Landing Page</h5>
                  <p>Web Design</p>
                </div>
              </div>
            </div>
          
          </div>
          ```
          
            </section>
          
            <!-- Footer -->
          
            <footer>
              <p>© 2025 Dribbble Clone Project. Created using Bootstrap.</p>
            </footer>
          
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
          
          </body>
          </html>
















# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-06 232258" src="https://github.com/user-attachments/assets/e99cbd8c-5a44-45c9-b98a-b13f91c5a707" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
