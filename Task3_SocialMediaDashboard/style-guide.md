<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="style.css">
  <title>My Dashboard | Social Metrics</title>
</head>
<body>
  <header>
    <h1 class="title">Social Metrics Dashboard</h1>
    <h3 class="text">Total Followers: 23,004</h3>
  </header>
  <main>
    <div class="main-title">
      <p>Toggle Dark Mode</p>
      <div class="toggle-container">
        <input type="checkbox" id="switch" name="theme">
        <label for="switch"></label>
      </div>
    </div>

    <section class="card-section">
      <div class="card fb">
        <div class="card-header">
          <img src="images/icon-facebook.svg" alt="fb-icon">
          <p>@user1</p>
        </div>
        <div class="card-body">
          <h1>1,987</h1>
          <p>followers</p>
        </div>
        <div class="card-footer">
          <img src="images/icon-up.svg" alt="up-icon">
          <p>+12 today</p>
        </div>
      </div>

      <!-- Add similar card structures for other social media platforms -->

    </section>

    <section class="overview-section">
      <h2 class="overview-title">Overview - Today</h2>

      <!-- Sample overview cards -->
      <div class="overview-card">
        <h3 class="page-views">Page Views</h3>
        <img class="fb-icon" src="images/icon-facebook.svg" alt="fb-icon">
        <h2>87</h2>
        <img class="up-down-icon" src="images/icon-up.svg" alt="up">
        <p class="percentage fb-up">+3%</p>
      </div>

      <!-- Add similar overview cards for various metrics -->

    </section>
  </main>
  <script src="index.js"></script>
</body>
</html>
