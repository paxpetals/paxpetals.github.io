<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pax Petals Flower Farm</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #fdf9f0;
      color: #2c2c2c;
      text-align: center;
    }
    header {
      padding: 20px;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #2c2c2c;
      font-weight: bold;
    }
    .logo {
      width: 150px;
      margin: 0 auto;
    }
    .hero, .section {
      padding: 40px 20px;
    }
    .hero h1, .section h2 {
      font-size: 2em;
      margin-bottom: 10px;
    }
    .hero p, .section p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 0 auto 30px;
    }
    .hero img {
      width: 90%;
      max-width: 700px;
      border-radius: 10px;
      margin-bottom: 30px;
    }
    .button-group a {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      background-color: #3a4f2d;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    .button-group a:hover {
      background-color: #4d6238;
    }
    iframe {
      width: 100%;
      border: none;
    }
    @media (max-width: 600px) {
      .hero h1, .section h2 {
        font-size: 1.5em;
      }
      .hero p, .section p {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/Pax Petals Logo.png" alt="Pax Petals Logo" class="logo" />
    <nav>
      <a href="#shop">Shop</a>
      <a href="#subscriptions">Subscriptions</a>
      <a href="#events">Events</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Pax Petals</h1>
    <p>
      a family-run flower farm in Somers, CT. We grow and sell fresh, seasonal flowers
      with love and care from our land to your hands.
    </p>
    <img src="https://images.unsplash.com/photo-1560184897-5bba9e31c4b3" alt="Fresh bouquet at flower stand" />
    <div class="button-group">
      <a href="#shop">Shop Bouquets</a>
      <a href="#subscriptions">Subscription Info</a>
      <a href="#events">Event Inquiries</a>
    </div>
  </section>

  <section class="section" id="subscriptions">
    <h2>Subscription Info</h2>
    <p>Sign up to receive fresh bouquets weekly, biweekly, or monthly.</p>
    <iframe src="https://docs.google.com/forms/d/e/YOUR_SUBSCRIPTION_FORM_ID/viewform?embedded=true" height="600">Loading…</iframe>
  </section>

  <section class="section" id="events">
    <h2>Event Inquiries</h2>
    <p>We provide custom arrangements for weddings, showers, and photo sessions.</p>
    <iframe src="https://docs.google.com/forms/d/e/YOUR_EVENT_FORM_ID/viewform?embedded=true" height="700">Loading…</iframe>
  </section>
</body>
</html>
