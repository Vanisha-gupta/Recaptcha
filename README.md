# Recaptcha by vanisha 

<!DOCTYPE html>
<html>
<head>
    <title>Website With reCAPTCHA</title>
      <script src="https://www.google.com/recaptcha/api.js" async defer></script>

    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            max-width: 400px;
            margin: 0 auto;

  background-color: rgba(0, 0, 255, 0.5); 

        }

        h1 {
            text-align: center;
        }

        form {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input[type="text"],
        input[type="email"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .g-recaptcha {
            margin-bottom: 10px;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        button:hover {
            background-color: #45a049;
        }
   .success {
            color: green;
            font-weight: bold;
        }

        .error {
            color: red;
            font-weight: bold;
        }
  

    </style>
</head>
<body>
    <h1>Website With reCAPTCHA</h1>
    <form method="POST" action="process_fo.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

         <div class="g-recaptcha" data-sitekey="6LdphsgnAAAAAN4xrRbebkDtXUTKcukM6wBcznbU
"></div>


        <button type="submit">Submit</button>
    </form>
</body>
</html
