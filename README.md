/* Reset default browser styles */
body, h1, h2, p, ul, li {
  margin: 0;
  padding: 0;
}

/* Basic styling for the page */
body {
  font-family: Arial, sans-serif;
  background-color: #f0f8ff; /* Light blue background */
  color: #333; /* Dark text color */
}

header {
  background-color: #4682b4; /* Steel Blue header background */
  color: #fff; /* White text color */
  padding: 20px;
}

header h1 {
  margin: 0;
  font-size: 24px;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  display: flex;
  padding: 20px;
}

.content {
  flex: 2; /* Take 2/3 of the available space */
  background-color: #fff; /* White background */
  padding: 20px;
}

.sidebar {
  flex: 1; /* Take 1/3 of the available space */
  background-color: #f0f0f0; /* Light gray background */
  padding: 20px;
}

footer {
  background-color: #4682b4; /* Steel Blue footer background */
  color: #fff;
  text-align: center;
  padding: 20px;
}

