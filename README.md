<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday Surprise</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: url('https://i.pinimg.com/736x/b3/5e/ea/b35eea6169d5b7e9de29d46bc4ed4257.jpg') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            /* Sharpening effect */
            image-rendering: -webkit-optimize-contrast;  /* Works on webkit browsers (Chrome/Safari) */
            image-rendering: crisp-edges;  /* Helps to sharpen the image */
        }
        #clickMe {
            font-size: 24px;
            color: white;
            background-color: pink;
            border: none;
            padding: 15px 30px;
            cursor: pointer;
            border-radius: 10px;
        }
        #clickMe:hover {
            background-color: lightpink;
        }
    </style>
</head>
<body>
    <button id="clickMe" onclick="window.location.href='Second Page.html'">Click me</button>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PDF Page</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: url('https://i.pinimg.com/736x/de/9c/63/de9c6340db6d60f5bece66d00998ff11.jpg') no-repeat center center fixed; 
            background-size: cover;
            font-family: Arial, sans-serif;
        }
        #downloadMe {
            margin-bottom: 20px;
            font-size: 36px; /* Increased font size */
            color: white;
            text-align: center;
        }
        #pdfContainer {
            width: 80%;
            height: 80vh;
            border: none;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        button {
            font-size: 24px;
            padding: 10px 20px;
            background-color: pink;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: lightcoral;
        }
    </style>
</head>
<body>
    <div id="downloadMe">Download me</div>
    <iframe id="pdfContainer" src="https://cdn.fbsbx.com/v/t59.2708-21/474441024_990616426461112_27699023821632378_n.pdf/HBD.pdf?_nc_cat=109&ccb=1-7&_nc_sid=2b0e22&_nc_ohc=WfEnoIH9Zr8Q7kNvgGZwyth&_nc_zt=7&_nc_ht=cdn.fbsbx.com&_nc_gid=A0PG5_FSnkHFS6vzYe5LwcN&oh=03_Q7cD1gH4rhaMpCfav-0OEd1VoLEeq1jq8MkGc4_IQoFw7gsxrQ&oe=6791B576&dl=1f"></iframe>
    <button onclick="window.location.href='Third Page.html'">Next</button>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify QR Code</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: url('https://cdn.visitgifu.com/wp/2020/03/dbbf82e0-img_3504.jpg') no-repeat center center fixed; 
            background-size: cover;
            font-family: Arial, sans-serif;
        }
        #listenToMe {
            margin-bottom: 20px;
            font-size: 36px;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6); /* Adds shadow for better readability */
        }
        #qrCode {
            width: 50%;
            max-width: 400px; /* Set a maximum width for large screens */
            height: auto;    /* Maintain the aspect ratio */
            margin-bottom: 20px; /* Add some space below the QR code */
        }
        button {
            margin-top: 20px;
            font-size: 20px;
            color: white;
            background-color: pink;
            border: none;
            padding: 15px 30px;
            cursor: pointer;
            border-radius: 10px;
        }
        button:hover {
            background-color: lightpink;
        }
    </style>
</head>
<body>
    <div id="listenToMe">Listen to Me</div>
    <img id="qrCode" src="https://scannables.scdn.co/uri/plain/jpeg/010101/white/640/spotify:track:03G92s34DOQCqcVZl0Gaoh" alt="Spotify QR Code">
    <button onclick="window.location.href='PBD.html'">Back to Start</button>
</body>
</html>
