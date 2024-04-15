# Virtual Wedding Planner
 Website for virtual wedding planning services.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Everlasting Events - Wedding Planning</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Everlasting Events</h1>
  <p>Creating unforgettable memories for your special day.</p>
  <nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact Us</a>
  </nav>
</header>

<main>
  <section id="banner">
    <img src="wedding-banner.jpg" alt="A couple embracing on their wedding day">
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <p>We offer a wide range of services to make your wedding planning smooth and stress-free.</p>
    <table>
      <caption>Wedding Planning Packages</caption>
      <thead>
        <tr>
          <th>Package</th>
          <th>Description</th>
          <th>Price</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Basic</td>
          <td>Vendor recommendations, budget planning, timeline creation.</td>
          <td>$1,500</td>
        </tr>
        <tr>
          <td>Deluxe</td>
          <td>Basic services + venue and decoration coordination.</td>
          <td>$2,500</td>
        </tr>
        <tr>
          <td>Premium</td>
          <td>Deluxe services + full wedding day management.</td>
          <td>$3,500</td>
        </tr>
      </tbody>
    </table>
    <p>We also offer custom packages to fit your specific needs. Contact us for a free consultation!</p>
  </section>

  <section id="more-info">
    <h2>Ready to start planning?</h2>
    <p>Get a free quote and download our wedding planning checklist!</p>
    <a href="get-quote.html">Get a Quote</a>
    <a href="checklist.pdf" download>Download Checklist</a>
  </section>
</main>

<footer>
  <p>&copy; Everlasting Events 2024</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Everlasting Events - Get a Quote</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Everlasting Events</h1>
  <p>Creating unforgettable memories for your special day.</p>
  <nav>
    <a href="../index.html">Home</a>
    <a href="../services.html">Services</a>
    <a href="../gallery.html">Gallery</a>
    <a href="../testimonials.html">Testimonials</a>
    <a href="../contact.html">Contact Us</a>
  </nav>
</header>

<main>
  <h2>Get a Quote for Your Dream Wedding</h2>
  <form action="quote-process.php" method="post">
    <label for="name">Your Name:</label>
    <input type="text" name="name" id="name" required>
    <br>
    <label for="email">Email Address:</label>
    <input type="email" name="email" id="email" required>
    <br>
    <label for="wedding-date">Wedding Date:</label>
    <input type="date" name="wedding-date" id="wedding-date" required>
    <br>
    <label for="num-guests">Estimated Number of Guests:</label>
    <input type="number" name="num-guests" id="num-guests" required>
    <br>
    <label for="package">Package Preference:</label>
    <select name="package" id="package
