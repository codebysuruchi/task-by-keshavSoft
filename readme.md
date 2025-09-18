### index.html code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Home - Light Brown Bootstrap 5 Theme</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    
    :root {
      --bs-primary: #a67c52;
      --bs-primary-rgb: 166, 124, 82;
      --bs-secondary: #d1bfa7;
      --bs-light: #f9f5f0;
      --bs-dark: #5c4231;
    }
    body {
      background-color: var(--bs-light);
      color: var(--bs-dark);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .navbar, .footer {
      background-color: var(--bs-primary);
    }
    .navbar .nav-link, .navbar-brand, .footer-text {
      color: var(--bs-light) !important;
    }
    .navbar .nav-link:hover, .navbar .nav-link:focus {
      color: var(--bs-secondary) !important;
    }
    .btn-primary {
      background-color: var(--bs-primary);
      border: none;
    }
    .btn-primary:hover, .btn-primary:focus {
      background-color: var(--bs-dark);
    }
    .hero-section {
      background-color: var(--bs-secondary);
      color: var(--bs-dark);
      padding: 4rem 2rem;
      border-radius: 0.5rem;
      margin-bottom: 2rem;
    }
    .card {
      border: none;
      border-radius: 0.5rem;
    }
    .card-title {
      color: var(--bs-primary);
    }
    .footer {
      padding: 1rem 0;
      text-align: center;
      color: var(--bs-light);
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">LightBrown</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu" aria-controls="navMenu"
              aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero-section text-center container">
    <h1 class="display-4 fw-bold">Welcome to Our Light Brown Theme Site</h1>
    <p class="lead mb-4">Clean, Responsive, and Elegant Bootstrap 5 Design</p>
    <a href="about.html" class="btn btn-primary btn-lg">Learn More</a>
  </section>

  <!-- Features Cards -->
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <div class="card-body text-center">
            <h5 class="card-title">Responsive Design</h5>
            <p class="card-text">Optimized for all device sizes with Bootstrap 5's grid and utilities.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <div class="card-body text-center">
            <h5 class="card-title">Modern UI Patterns</h5>
            <p class="card-text">Extracted from official Bootstrap examples to ensure clean, tested components.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <div class="card-body text-center">
            <h5 class="card-title">Easy Customization</h5>
            <p class="card-text">Light brown theme with consistent spacing and colors for a polished look.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p class="footer-text mb-0">&copy; 2025 LightBrown Theme. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

### About.html code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About - Light Brown Bootstrap 5 Theme</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    /* Same CSS as in index.html */
    :root {
      --bs-primary: #a67c52;
      --bs-primary-rgb: 166, 124, 82;
      --bs-secondary: #d1bfa7;
      --bs-light: #f9f5f0;
      --bs-dark: #5c4231;
    }
    body {
      background-color: var(--bs-light);
      color: var(--bs-dark);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .navbar, .footer {
      background-color: var(--bs-primary);
    }
    .navbar .nav-link, .navbar-brand, .footer-text {
      color: var(--bs-light) !important;
    }
    .navbar .nav-link:hover, .navbar .nav-link:focus {
      color: var(--bs-secondary) !important;
    }
    .btn-primary {
      background-color: var(--bs-primary);
      border: none;
    }
    .btn-primary:hover, .btn-primary:focus {
      background-color: var(--bs-dark);
    }
    .card {
      border: none;
      border-radius: 0.5rem;
    }
    .card-title {
      color: var(--bs-primary);
    }
    .footer {
      padding: 1rem 0;
      text-align: center;
      color: var(--bs-light);
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">LightBrown</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu" aria-controls="navMenu"
              aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- About Section -->
  <section class="container my-5">
    <h2 class="mb-4 text-center" style="color: var(--bs-primary);">About Our Services</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card shadow-sm p-3 h-100">
          <div class="card-body text-center">
            <h5 class="card-title">Web Development</h5>
            <p class="card-text">Building responsive, modern websites using the latest Bootstrap 5 standards.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3 h-100">
          <div class="card-body text-center">
            <h5 class="card-title">UI/UX Design</h5>
            <p class="card-text">Creating clean and user-friendly interfaces with consistent themes and layouts.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3 h-100">
          <div class="card-body text-center">
            <h5 class="card-title">Consulting</h5>
            <p class="card-text">Expert advice and training on Bootstrap usage and front-end best practices.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p class="footer-text mb-0">&copy; 2025 LightBrown Theme. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

### contact.html code:
```
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact - Light Brown Bootstrap 5 Theme</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    /* Same CSS as above */
    :root {
      --bs-primary: #a67c52;
      --bs-primary-rgb: 166, 124, 82;
      --bs-secondary: #d1bfa7;
      --bs-light: #f9f5f0;
      --bs-dark: #5c4231;
    }
    body {
      background-color: var(--bs-light);
      color: var(--bs-dark);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .navbar, .footer {
      background-color: var(--bs-primary);
    }
    .navbar .nav-link, .navbar-brand, .footer-text {
      color: var(--bs-light) !important;
    }
    .navbar .nav-link:hover, .navbar .nav-link:focus {
      color: var(--bs-secondary) !important;
    }
    .btn-primary {
      background-color: var(--bs-primary);
      border: none;
    }
    .btn-primary:hover, .btn-primary:focus {
      background-color: var(--bs-dark);
    }
    .footer {
      padding: 1rem 0;
      text-align: center;
      color: var(--bs-light);
    }
    .form-control:focus {
      border-color: var(--bs-primary);
      box-shadow: 0 0 0 0.2rem rgba(166,124,82,.25);
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">LightBrown</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu" aria-controls="navMenu"
              aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contact Form -->
  <section class="container my-5" style="max-width: 600px;">
    <h2 class="mb-4 text-center" style="color: var(--bs-primary);">Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="nameInput" class="form-label">Name</label>
        <input type="text" class="form-control" id="nameInput" placeholder="Your full name" required />
      </div>
      <div class="mb-3">
        <label for="emailInput" class="form-label">Email address</label>
        <input type="email" class="form-control" id="emailInput" placeholder="name@example.com" required />
      </div>
      <div class="mb-3">
        <label for="messageInput" class="form-label">Message</label>
        <textarea class="form-control" id="messageInput" rows="5" placeholder="Write your message here..." required></textarea>
      </div>
      <button type="submit" class="btn btn-primary w-100">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p class="footer-text mb-0">&copy; 2025 LightBrown Theme. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```