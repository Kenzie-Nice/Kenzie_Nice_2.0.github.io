
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <style>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css">
  <style>
    /* Applying the Rinse font */
    body {
      font-family: rinse, sans-serif;
      font-style: normal;
      font-weight: 400;
    }
    
    /* Class selector */
    .canvas {
      background-color: rgb(0, 0, 255);
    }

    .text-blue {
      color: blue;
    }
    #paragraph {
      font-weight: bold;
    }

    /* Hover effect */
    .hover-text {
      display: none;
    }

    .text-blue:hover + .hover-text {
      display: inline;
    }
  </style>
</head>
<body>

  <h1>This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are actually made from skull caps!!</p>
  <p class="hover-text">The question is if these skulls where human or not though.</p>

  <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups</p>

  <h2>
    <p>
      See, here are some more cups... Colorful, right?
    </p>
  </h2>

  <img src="preview16.jpg" alt="Placeholder Image" class="photo">

</body>
</html>
