<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <style>
        /* Basic styling for the example */
        body, input {
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
            margin-top: 100px;
        }
        .google-logo {
            margin-bottom: 20px;
        }
        .search-bar {
            width: 400px;
            padding: 10px;
            font-size: 16px;
        }
        .search-button {
            padding: 10px 15px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="google-logo" src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_light_color_272x92dp.png" alt="Google Logo" width="272" height="92">
        <form action="https://www.google.com/search" method="get">
            <input class="search-bar" type="text" name="q" aria-label="Search" placeholder="Search Google">
            <br>
            <input class="search-button" type="submit" value="Google Search">
            <input class="search-button" type="button" value="I'm Feeling Lucky">
        </form>
    </div>
</body>
</html>
