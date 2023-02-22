<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Building and Construction Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>
          <h3>Construction</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button onclick="bookService('Construction')">Book Now</button>
        </li>
        <li>
          <h3>Renovation</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button onclick="bookService('Renovation')">Book Now</button>
        </li>
        <li>
          <h3>Painting</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button onclick="bookService('Painting')">Book Now</button>
        </li>
      </ul>
    </section>
    
    <section id="work-done">
      <h2>Work Done</h2>
      <ul>
        <li>
          <h3>Construction</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </li>
        <li>
          <h3>Renovation</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </li>
        <li>
          <h3>Painting</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </li>
      </ul>
    </section>
    
    <section id="invoice">
      <h2>Invoice</h2>
      <div id="invoice-details"></div>
    </section>
  </main>
  
  <footer>
    <p>&copy; Building and Construction Website 2023</p>
  </footer>
  
  <script src="script.js"></script>
</body>
</html>
/* General Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  background-color: #f0f0f0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 1rem;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul li {
  margin-right: 1rem;
}


