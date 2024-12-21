# Project Responsive Web Design using Bootstrap
# Date:
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
# discover.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="bootstrapex-10.html">Discover</a></li>
          <li class="nav-item"><a class="nav-link" href="discover.html">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="bg-light py-5 text-center">
    <div class="container">
      <h1>Welcome to Dribbble Clone</h1>
      <p class="lead">Showcase your creative work and discover inspiring designs.</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </header>

  <!-- Content Section -->
  <section class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Explore Shots</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="https://th.bing.com/th/id/OIG3.80EN2JPNx7kp5VqoB5kz" class="card-img-top" alt="Design 1">
            <div class="card-body">
              <h5 class="card-title">Design 1</h5>
              <p class="card-text">A creative shot to inspire.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-C_UAhXq9GfuGO452EEzfbKnh1viQB9EDBQ&s" class="card-img-top" alt="Design 2">
            <div class="card-body">
              <h5 class="card-title">Design 2</h5>
              <p class="card-text">Another stunning piece of work.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://avatars.mds.yandex.net/i?id=b507a2b8d9382967a186c654f1eeaa74-5262078-images-taas-consumers&n=27&h=480&w=480" class="card-img-top" alt="Design 3">
            <div class="card-body">
              <h5 class="card-title">Design 3</h5>
              <p class="card-text">Let your imagination flow.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white py-3 text-center">
    <p>&copy; 2024 | Designed by Amirtha Varshini M</p>
  </footer>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  
</body>
</html>
```
# about.html
```
<html>
    <head>
        <title>about</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-light" id="about">
            <div class="container">
              <h2 class="text-center mb-4">About Us</h2>
              <p class="text-center">Dribbble Clone is a platform for designers to showcase their work and get inspired. Whether you're a graphic designer, illustrator, or UI/UX expert, our community is here to help you grow and connect with others.</p>
              <div class="row mt-4">
                <div class="col-md-6">
                  <h5>Our Mission</h5>
                  <p>To provide a space for creatives to share their work, gain feedback, and find inspiration from peers around the world.</p>
                </div>
                <div class="col-md-6">
                  <h5>Why Join Us?</h5>
                  <p>By joining Dribbble Clone, you become part of a vibrant community that celebrates creativity and innovation in design.</p>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by Amirtha Varshini M</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

        
</html>
  ```
# project.html
```
<html>
    <head>
        <title>project</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">


    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5" id="projects">
            <div class="container">
              <h2 class="text-center mb-4">Projects</h2>
              <p class="text-center">Explore various design projects contributed by our talented community members.</p>
              <div class="row">
                <div class="col-md-4">
                  <div class="card">
                    <img src="space.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                      <h5 class="card-title">Project 1</h5>
                      <p class="card-text">A creative web design project.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="mobile template.jpg" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                      <h5 class="card-title">Project 2</h5>
                      <p class="card-text">An innovative mobile app design.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="branding.jpg" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                      <h5 class="card-title">Project 3</h5>
                      <p class="card-text">A branding and identity design.</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by Amirtha Varshini M</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
          

    </body>
</html>
```
# signup.html
```
<html>
    <head>
        <title>signup</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-primary text-white" id="signup">
            <div class="container">
              <h2 class="text-center mb-4">Sign Up</h2>
              <p class="text-center">Join the Dribbble Clone community and start sharing your work today!</p>
              <form class="mx-auto" style="max-width: 500px;">
                <div class="mb-3">
                  <label for="username" class="form-label">Username</label>
                  <input type="text" class="form-control" id="username" placeholder="Enter your username" required>
                </div>
                <div class="mb-3">
                  <label for="email" class="form-label">Email address</label>
                  <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                  <label for="password" class="form-label">Password</label>
                  <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <button type="submit" class="btn btn-light w-100">Sign Up</button>
              </form>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>
```

# OUTPUT:
# discover.html
![Screenshot (2026)](https://github.com/user-attachments/assets/f67dbb42-c80f-4018-a200-662ac5a70510)
# about.html
![Screenshot (2027)](https://github.com/user-attachments/assets/31268b2c-7b2e-4d6f-a6a9-dd3c96b08aed)
# project.html
![Screenshot (2028)](https://github.com/user-attachments/assets/c21b9a27-05e9-4288-8652-6183c914ebd9)




# signup.html
![Screenshot (2029)](https://github.com/user-attachments/assets/e275b2b5-c98a-4fd8-88ed-4f52cf4434bf)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
