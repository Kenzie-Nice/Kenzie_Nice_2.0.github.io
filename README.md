<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css"> 
  <style>
    body {
      background-color: tan;
      margin: 0; /* Reset default margin */
      padding: 0; /* Reset default padding */
    }
    .canvas {
      background-color: rgb(0, 0, 355);
      margin-bottom: 20px; /* Add some space below the heading */
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
    .dropdown {
      position: relative;
      display: inline-block;
      margin-bottom: 20px; /* Add some space below the dropdown */
    }
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 260px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.9);
      z-index: 1;
      top: calc(100% + 5px); /* Position below the button with a small gap */
      left: 0;
    }
    .dropdown:hover .dropdown-content {
      display: block;
    }

  #paragraph {
      font-weight: bold;
      margin-top: 20px; /* Add some space above the paragraph */
    }
    .hover-text {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      border: 1px solid black;
      padding: 10px;
      color: #3e2723; /* Dark brown color */
    }
    .text-blue:hover + .hover-text {
      display: block;
    }
    .photo {
      width: 550px;
    }
  </style>
</head>
<body>

  <h1 class="canvas">This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are actually made from skull caps!!
    <span class="hover-text">It leaves us to question though what and where these skulls came from though.</span>
  </p>

  <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups. They are everywhere around us and really...we need them. Even if once using cupped hands to leaves, bones to then woods and eventually metals and now plastics. Cups have grown with humans our entire lives and will still continue to do so in different methods, designs and even uses!</p>

  <h2>
    <p>
      See, here are some more cups... Colorful, right?
    </p>
  </h2>

  <img src="coffee-mug_NVKXLIKJ25.jpg" alt="Placeholder Image" class="photo">
  <img src="tea-black-tea-drink-tea-cup-preview.jpg" alt="Placeholder Image" class="photo">

  <div class="dropdown">
    <button>Look at me</button>
    <div class="dropdown-content">
      <p>Fun Fact! A regular coffee cup holds about 12 ounces, where as a tea cup holds only about 6 ounces. So, if you drink tea in a coffee mug, it's like drinking 2 cups of tea at once! </p>
    </div>
  </div>

</body>
</html>
