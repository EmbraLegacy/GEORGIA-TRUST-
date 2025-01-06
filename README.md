index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Georgia Trust™</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to Georgia Trust™</h1>
  </header>

  <section>
    <h2>Account Balance</h2>
    <p>Your account balance is: <strong>USD 1,000,000</strong></p>
  </section>

  <footer>
    <p>Contact: <a href="mailto:doyullee29@outlook.com">doyullee29@outlook.com</a></p>
    <p>Phone: <a href="tel:+82-10-8309-5685">+82-10-8309-5685</a></p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
style.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background-color: #333;
  color: white;
  padding: 10px 0;
  text-align: center;
}

section {
  padding: 20px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px 0;
}
script.js
document.addEventListener('DOMContentLoaded', function() {
  console.log("Georgia Trust™ site loaded.");
});
