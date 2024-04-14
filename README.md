
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css""> 
  <style>
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
    /* Applying the Rinse font */
    body {
      font-family: rinse, sans-serif;
      font-style: normal;
      font-weight: 400;
    }
  </style>
</head>
<body>

  <h1>This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are actually made from skull caps!! <span class="hover-text">This text appears when you hover over the blue text.</span></p>

  <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups</p>

  <h2>
    <p>
      See, here are some more cups... Colorful, right?
    </p>
  </h2>

  <img src="preview16.jpg" alt="Placeholder Image" class="photo">

</body>
</html>
