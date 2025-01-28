# SABERKAS 
Pertubuhan Belia Kebangsaan Bersatu Sarawak
<h1 style="color🟦;">
<a <a href="https://www.example.com/login" style="display:inline-block; background-color:#4CAF50; color:white; padding:10px 20px; text-align:center; text-decoration:none; border-radius:5px;">
    Log In
<a document.getElementById('loginButton').addEventListener('click', function() {
    var username = document.getElementById('username').value;
    var password = document.getElementById('password').value;

    // Perform validation (e.g., check if fields are empty)
    if (username === '' || password === '') {
        alert('Please enter both username and password.');
        return;
    }

    // Example: Log the username and password to the console (you should send this data to your server)
    console.log('Username:', username);
    console.log('Password:', password);

    // Here you would typically send the credentials to your server for validation
    // Example using fetch:
    /*
    fetch('/login', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({ username: username, password: password })
    })
    .then(response => response.json())
    .then(data => {
        if (data.success) {
            // Redirect to another page or show a success message
            window.location.href = '/dashboard';
        } else {
            // Show an error message
            alert('Login failed: ' + data.message);
        }
    })
    .catch(error => {
        console.error('Error:', error);
    });
    */
});
