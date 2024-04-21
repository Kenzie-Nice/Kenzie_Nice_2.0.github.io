
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css"> 
  <style>
    /* Class selector */
    .canvas {
      background-color: rgb(0, 0, 255);
    }

.text-blue {
  color: blue;
  font-style: italic; /* Added font style */
  font-weight: bold; /* Added font weight */
  border: 10px outset black; /* Border with outset style */
  padding: 10px; /* Padding */
  overflow: hidden; /* Overflow */
  display: inline-block; /* Display */
  margin: 10px; /* Margin */
  position: relative; /* Position */
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
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
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

  <div class="dropdown">
    <button>Dropdown</button>
    <div class="dropdown-content">
      <p>Dropdown Content Here</p>
    </div>
  </div>

</body>
</html>

</body>
</html>


