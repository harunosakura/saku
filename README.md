<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GIF Page</title>
    <style>
        body {
            background-color: #111; /* Dark background */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ensure full viewport height */
            margin: 0; /* Remove default margins */
            overflow: hidden; /* Hide scrollbars if content overflows */
        }

        .neon-border {
            width: 90vw; /* Adjust as needed */
            height: 90vh; /* Adjust as needed */
            max-width: 800px; /* Set a maximum width */
            max-height: 600px; /* Set a maximum height */
            border: 4px solid;
            border-image: linear-gradient(to right, #0f0, #0ff, #f0f, #f00, #f0f, #0ff, #0f0) 1;
            border-radius: 10px; /* Rounded corners (optional) */
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.5); /* Neon glow */
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        img {
          max-width: 100%; /* Ensure GIF fits within the container */
          max-height: 100%;
        }

    </style>
</head>
<body>

    <div class="neon-border">
        <img src="your_gif.gif" alt="Centered GIF">  </div>

</body>
</html>
