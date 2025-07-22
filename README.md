# DeadlyDetailsTC
True Crime Blogsite
<!DOCTYPE html>
<html>
<head>
  <title>True Crime News</title>
  <style>
    body {
      font-family: Copperplate Gothic Light, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: white;
    }

    header {
      background: #B71C1C;
      color: white;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header h1 {
      margin: 0;
      color: white;
    }

    nav {
      padding: 0;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background-image: url('https://i.etsystatic.com/23877641/r/il/9a8a03/5618036505/il_1080xN.5618036505_cf3j.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: crimson;
      padding: 40px 20px;
      text-align: center;
    }

    .hero .headline-box,
    .hero .summary-box {
      background-color: #2B2A2A;
      color: white;
      display: inline-block;
      padding: 15px 25px;
      margin: 10px auto;
      border-radius: 5px;
    }

    .hero .wireframe-box {
      width: 100%;
      max-width: 600px;
      height: 400px;
      border: 2px dashed #ccc;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f9f9f9;
      margin: 20px auto 0 auto;
    }

    .hero .wireframe-box img {
      max-width: 100%;
      max-height: 100%;
      object-fit: cover;
    }

    .trending-section {
      background-color: #B71C1C;
      padding: 40px 20px;
    }

    .section-title {
      text-align: center;
      color: white;
      font-size: 1.5em;
      margin-bottom: 20px;
    }

    .content {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      color: white;
      text-align: center;
    }
    .featured-wrapper {
      border: 3px solid #B71C1C;
      background-color: #B71C1C;
      padding: 20px;
      max-width: 700px;
      margin: 0 auto;
      border-radius: 8px;
    }

    .card {
      background: #2B2A2A;
      width: 300px;
      padding: 15px;
      border: 1px solid #ccc;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
      color: white;
    }

    .card h3 {
      margin-top: 0;
      color: white;
    }

    .wireframe-box {
      width: 100%;
      height: 120px;
      border: 2px dashed #ccc;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #2B2A2A;
      margin-bottom: 10px;
      font-size: 1em;
      color: white;
    }
    
    .wireframe-box img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    footer {
      background: #FFFFFF;
      color: black;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    footer p {
      color: black;
    }
  </style>
</head>
<body>

  <!-- Header Section with Navigation -->
  <header>
    <h1>Deadly Details True Crime</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Well-Known Killers</a>
      <a href="#">Missing Persons</a>
      <a href="#">Cold Cases</a>
      <a href="#">Serial Killers</a>
    </nav>
  </header>

  <div style="background-color: #2B2A2A; height: 20px; width: 100%;"></div>

  <!-- Hero Section -->
  <div class="hero">
    <div class="featured-wrapper">
      <div class="headline-box">
        <h2>Featured Story</h2>
      </div>
      <div class="wireframe-box">
        <img src="https://s.abcnews.com/images/US/kohberger-court_hpMain_20230103-154722.jpg?w=992" alt="Victims">
      </div>
      <div class="summary-box">
        <p>Brian Kohlberger Plead Guilty to Four Life Sentences</p>
      </div>
    </div>
  </div> 

  <div style="background-color: #2B2A2A; height: 20px; width: 100%;"></div>

  <!-- Trending Section -->
  <div class="trending-section">
    <div class="section-title">Trending</div>
    <div class="content">
      <div class="card">
        <h3>Gilgo Beach Killings</h3>
        <div class="wireframe-box"><img src="https://new-cdn.mamamia.com.au/mamamia-pwa.appspot.com/cms_images/originals/4l3LcQyi5S7rU5O0tZPA_1689659304463.png" alt="Victims"></div>
        <p>Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor.</p>
      </div>
      <div class="card">
        <h3>Disappearance of Madeleine McCann</h3>
        <div class="wireframe-box"><img src="https://nypost.com/wp-content/uploads/sites/2/2020/08/madeleine-mccann.jpg?quality=75&strip=all" alt="Victims"></div>
        <p>Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor.</p>
      </div>
      <div class="card">
        <h3>The Zodiac Killer</h3>
        <div class="wireframe-box"><img src="https://images.saymedia-content.com/.image/c_limit%2Ccs_srgb%2Cq_auto:eco%2Cw_700/MTkyMzM2MTUyNzgxNTMwMzU0/12-shocking-facts-about-the-zodiac-killer.webp" alt="Victims"></div>
        <p>Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor.</p>
      </div>
    </div>
  </div>c

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 Deadly Details True Crime | Contact | Privacy Policy</p>
  </footer>

</body>
</html>
