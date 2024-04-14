<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css"> 
  <style>
    /* Applying the Rinse font */
    body {
      font-family: rinse, sans-serif;
      font-style: normal;
      font-weight: 400;
    }

    /* Basic styling for heading */
    h1 {
      font-size: 24px;
      color: #333;
      margin-bottom: 20px;
    }

    /* Basic styling for paragraphs */
    p {
      font-size: 16px;
      color: #666;
      margin-bottom: 15px;
    }

    /* Hover effect */
    .hover-text {
      display: none;
    }
    .text-blue:hover + .hover-text {
      display: inline;
    }

    /* Additional styling */
    h2 {
      font-size: 20px;
      color: #444;
      margin-bottom: 15px;
    }

    .photo {
      max-width: 100%;
      height: auto;
    }

    .canvas {
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 10px;
      background-color: #f9f9f9;
    }
  </style>
</head>
<body>

  <h1>This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are actually made from skull caps!! <span class="hover-text"> It leaves to question though what and where these skulls came from though.</span></p>

  <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups</p>

  <h2>See, here are some more cups... Colorful, right?</h2>

  <div class="canvas">
    <img src="preview16.jpg" alt="Placeholder Image" class="photo">
  </div>

</body>
</html>
