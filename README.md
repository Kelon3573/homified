
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>homified</title>

  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      margin: 0;
      overflow-x: hidden;
    }

    /* HEADER */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      width: 100%;
      box-sizing: border-box;
    }

    .HMF {
      font-size: 20px;
      font-weight: bold;
      font-style: italic;
      color: antiquewhite;
      letter-spacing: 3px;
    }

    .links {
      display: flex;
      list-style: none;
      gap: 15px;
      margin: 0;
      padding: 0;
    }

    .links a {
      color: antiquewhite;
      text-decoration: none;
      font-size: 14px;
    }

    .search-container {
      display: flex;
      align-items: center;
      border: 1px solid antiquewhite;
      border-radius: 6px;
      padding: 4px 8px;
    }

    .search-container input {
      background: transparent;
      border: none;
      color: white;
      outline: none;
      width: 100px;
      font-size: 12px;
    }

    .search-container button {
      background: transparent;
      border: none;
      color: antiquewhite;
      cursor: pointer;
    }

    /* BANNER */
    #banner {
      position: relative;
      width: 100%;
      height: 80vh;
      background-image: url("her.jpeg");
      background-size: cover;
      background-position: center;
    }

    .banner-text {
      position: absolute;
      top: 50%;
      left: 25%;
      transform: translate(-50%, -50%);
      color: antiquewhite;
      font-weight: bold;
      font-size: 30px;
    }

    .accent {
      color: burlywood;
      font-size: 40px;
    }

    .shop-btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 12px 24px;
      border: 1px solid antiquewhite;
      background: antiquewhite;
      color: black;
      text-decoration: none;
      font-size: 14px;
      margin-top: 10px;
    }

    .explore {
      color: white;
      text-decoration: underline;
      margin-left: 15px;
      font-size: 14px;
    }

    /* SIDE NAV */
    .side-nav {
      position: fixed;
      right: 30px;
      top: 50%;
      transform: translateY(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      color: antiquewhite;
    }

    .side-nav a {
      color: antiquewhite;
      text-decoration: none;
      opacity: 0.7;
    }

    .line {
      width: 1px;
      height: 30px;
      background: antiquewhite;
      opacity: 0.6;
    }

    /* FEATURES */
    .features {
      max-width: 1200px;
      margin: 60px auto;
      display: flex;
      justify-content: space-between;
      border: 1px solid #222;
      border-radius: 16px;
      padding: 30px 10px;
    }/* Each column */
.feature{
  flex:1;
  text-align:center;
  padding:20px 25px;
  color:#eaeaea;
  position:relative;
}

/* Vertical divider */
.feature:not(:last-child)::after{
  content:"";
  position:absolute;
  right:0;
  top:20%;
  height:60%;
  width:1px;
  background:#222;
}

 .feature {
      flex: 1;
      text-align: center;
      padding: 20px; }

    .feature:not(:last-child)::after {
      content: "";
      position: absolute;
      right: 0;
      top: 20%;
      height: 60%;
      width: 1px;
      background: #222;
    }

    .icon {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .feature h3 {
      font-size: 14px;
      letter-spacing: 1px;
    }

    .feature p {
      font-size: 13px;
      color: #aaa;
    }

    @media (max-width: 800px) {
      .features {
        flex-direction: column;
      }

      .feature:not(:last-child)::after {
        display: none;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header class="header">
    <div class="HMF">H0MIFIED</div>

    <ul class="links">
      <li><a href="#">Home</a></li>
      <li><a href="#">Collections</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Lookbook</a></li>
      <li><a href="#">Contact</a></li>
    </ul>

    <div class="search-container">
      <input type="text" placeholder="Search">
      <button>➜</button>
    </div>
  </header>

  <!-- BANNER -->
  <section id="banner">
    <div class="banner-text">
      <h1>
        CLOTHES THAT<br>
        FEEL LIKE <span class="accent">HOME.</span>
      </h1>

      <p>Comfort. Warmth. Effortless style.<br>Wherever you go.</p>

      <a href="#" class="shop-btn">
        SHOP COLLECTION →
      </a>

      <a href="#" class="explore">EXPLORE MORE</a>
    </div>
  </section>

  <!-- SIDE NAV -->
  <div class="side-nav">
    <a href="#page1">01</a>
    <div class="line"></div>
    <a href="#page2">02</a>
    <a href="#page3">03</a>
  </div>

  <!-- FEATURES -->
  <section class="features">
    <div class="feature">
      <div class="icon">◎</div>
      <h3>COMFORT FIRST</h3>
      <p>Soft fabrics and relaxed fits designed for all-day ease.</p>
    </div>

    <div class="feature">
      <div class="icon">✱</div>
      <h3>TIMELESS STYLE</h3>
      <p>Minimal, clean, and versatile pieces for every part of life.</p>
    </div>

    <div class="feature">
      <div class="icon">◇</div>
      <h3>PREMIUM QUALITY</h3>
      <p>Crafted with care using the finest materials.</p>
    </div>

    <div class="feature">
      <div class="icon">🍃</div>
      <h3>MADE TO LAST</h3>
      <p>Sustainable choices for a better tomorrow.</p>
    </div>
  </section>

</body>
</html>
