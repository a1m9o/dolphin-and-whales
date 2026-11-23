# dolphin-and-whales

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Website</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #f8f5f2;
  color: #292929;
}

header {
  padding: 25px;
  text-align: center;
  background: #e8dcd3;
}

header h1 {
  font-size: 36px;
  letter-spacing: 3px;
}

nav {
  padding: 18px;
  text-align: center;
}

nav a {
  color: #292929;
  text-decoration: none;
  margin: 15px;
}

.hero {
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 42px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 17px;
  margin-bottom: 30px;
}

button {
  padding: 14px 28px;
  background: #a98976;
  color: white;
  border: none;
  border-radius: 25px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background: #806453;
}

section {
  padding: 55px 20px;
  text-align: center;
}

footer {
  background: #e8dcd3;
  padding: 25px;
  text-align: center;
}
</style>
</head>

<body>

<header>
  <h1>MY WEBSITE</h1>
  <p>A little place on the internet</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
  <h2>Welcome!</h2>
  <p>Welcome to my website. Have a look around!</p>
  <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})">
    Discover more
  </button>
</div>

<section id="about">
  <h2>About</h2>
  <p>This is where you can write about your website.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Get in touch!</p>
</section>

<footer>
  <p>© 2026 My Website</p>
</footer>

</body>
</html>
