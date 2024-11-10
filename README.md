
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>How's Your Day?</title>
  <!-- Link to Google Fonts for a better font (Poppins) -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #ad95ed;
      text-align: center;
      margin: 0;
    }

    h1 {
      font-family: 'Poppins', sans-serif; /* Applied the Poppins font */
      font-size: 3em;
      color: #524b51;
      margin-bottom: 5px;
      text-transform: uppercase;
      letter-spacing: 2px;
      font-weight: bold;
    }

    .button {
      margin: 5px;
      padding: 10px 20px;
      font-size: 1.2em;
      color: #ffffff;
      background-color: #7129e5;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .button:hover {
      background-color: #430340;
    }
  </style>
</head>
<body>

  <h1>hi babyyyyy</h1>
  <h1>miss me?</h1>
  <a href="second.html">
    <button class="button">Yes</button>
  </a>
  <a href="third.html">
    <button class="button">no </button>
  </a>
  <script>
    function goToPage(mood) {
      window.location.href = mood + ".html"; // Redirects to the page based on the mood selected
    }
  </script>

</body>
</html>
