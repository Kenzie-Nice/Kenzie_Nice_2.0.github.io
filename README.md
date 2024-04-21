<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css"> 
  <style>
    /* Class selector */
    .canvas {
      background-color: rgb(0, 0, 355);
    }

    .text-blue {
      color: blue;
      font-style: italic; 
      font-weight: bold; 
      border: 10px outset black; 
      padding: 18px; 
      overflow: hidden;
      display: inline-block;
      margin: 10px; 
      position: relative; 
    }

    /* Dropdown */
    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 260px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.9);
      z-index: 1;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    #paragraph {
      font-weight: bold;
    }

    /* Hover effect */
    .hover-text {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      border: 1px solid black;
      padding: 10px;
    }

    .text-blue:hover + .hover-text {
      display: block;
    }

    /* Set width for the photo */
    .photo {
      width: 400px;
    }
  </style>
</head>
<body>

  <h1 class="canvas">This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are actually made from skull caps!!
    <span class="hover-text">It leaves to question though what and where these skulls came from though.</span>
  </p>

  <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups</p>

  <h2>
    <p>
      See, here are some more cups... Colorful, right?
    </p>
  </h2>

  <img src="preview16.jpg" alt="Placeholder Image" class="photo">
  <img src="tea-black-tea-drink-tea-cup-preview.jpg" alt="Placeholder Image" class="photo">

  <div class="dropdown">
    <button>Look at me</button>
    <div class="dropdown-content">
      <p>Fun Fact! A regular coffee cup holds about 12 ounces, where as a tea cup holds only about 6 ounces. So if you drink tea in a coffee mug its like drinking 2 cups of tea at once! </p>
    </div>
  </div>

</body>
</html>
