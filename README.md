# SABERKAS   
Pertubuhan Belia Kebangsaan Bersatu Sarawak
<p>Ini adalah halaman utama. Klik butang di bawah untuk log masuk:</p>
<a href="login.html" style="display:inline-block; background-color:#4CAF50; color:white; padding:10px 20px; text-align:center; text-decoration:none; border-radius:5px;">
    Log In
</a>
 <!DOCTYPE html>
 <html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Halaman Utama</title>
</head>
<body>
    
  <!-- Button for login -->
  <button id="loginButton" style="background-color:#4CAF50; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer;">Login</button>

  <script>
    // Redirect to login.html when button is clicked
    document.getElementById('loginButton').addEventListener('click', function () {
      window.location.href = 'login.html'; // Halaman yang akan dibuka
    });
  </script>
</body>
</html>
