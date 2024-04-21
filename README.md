<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beginner HTML Page</title>
  <link rel="stylesheet" href="https://use.typekit.net/txt4pqn.css"> 
  <style>
    body {
      background-color: tan;
      margin: 0;
      padding: 0; 
    }

  .content-container {
      border: 12px solid #3e2723;
      padding: 20px; 
      margin: 20px; 
    }

  .canvas {
      background-color: rgb(0, 0, 355);
      margin-bottom: 20px;
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
      margin-bottom: 20px;
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
      border: 3px solid black;
      padding: 10px;
      color: #3e2723; /* Dark brown color */
    }

   .text-blue:hover + .hover-text {
      display: block;
    }
    .photo {
      width: 450px;
    }
  </style>
</head>
<body>

  <div class="content-container">
    <h1 class="canvas">This is a page about cups</h1>

  <p class="text-blue">We use cups all the time; as humans, we have had cups around for our entire existence. Fun, right? Did you know that the oldest cups ever found are made from skull caps!!
      <span class="hover-text">It leaves us to question though what and where these skulls came from though.</span>
    </p>
    <p id="paragraph">There are many types of cups. Mugs, Coffee Cups, Teacups, Paper cups</p>
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
        <p>Fun Fact! A regular coffee cup holds about 12 ounces, where as a tea cup holds only about 6 ounces. So if you drink tea in a coffee mug its like drinking 2 cups of tea at once! </p>
      </div>
    </div>
  </div>

</body>
</html>
