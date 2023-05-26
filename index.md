<html>
<head>
  <title>My Website</title>
  <style>
    body {
      background-color: #fff;
      font-family: Arial, sans-serif;
      display: flex;
      align-items: center;
    }

    .top-bar {
  background-color: #f0f0f0; /* Set the top bar color to light grey */
  width: 100%;
  padding: 20px; /* Increase the padding value to make the top bar thicker */
  display: flex; /* Add this line to enable flexbox layout */
  justify-content: flex-start; /* Align the content to the left */
  align-items: center; /* Vertically center the content */
  position: fixed; /* Position the top bar */
  top: 0; /* Position it at the top */
  box-sizing: border-box; /* Include padding and border in the total width */
}

    .top-bar a {
  text-decoration: none;
  color: #333;
  font-size: 30px;
  font-weight: bold; /* Add this line to make the text bold */
  margin-left: 225px; /* Adjust the margin value to move the content along the top bar */
}


    .sidebar {
      width: 200px;
      height: 100%;
      background-color: #fff;
      border: 1px solid #ccc;
      border-radius: 8px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      margin-top: 80px; /* Adjust this value to shift the sidebar down */
      margin-left: 200px; /* Adjust the margin value to move the content along the top bar */
    }

    .sidebar ul {
      list-style-type: none;
      padding: 0;
      margin: 40;
    }

    .sidebar li {
      margin-bottom: 10px;
    }

    .sidebar a {
      display: block;
      padding: 10px;
      text-decoration: none;
      color: #333;
    }

    .sidebar a:hover {
      background-color: #f0f0f0;
    }

    .main-content {
      padding: 20px;
    }

    .main-content h1 {
      font-size: 36px;
    }

    .main-content h2 {
      font-size: 24px;
    }
  </style>
</head>
<body>
  <!-- Start of HTML -->
  <div class="sidebar">
    <ul>
      <li><a href="Webpages/data.html">Data</a></li>
      <li><a href="Webpages/analysis.html">Analysis</a></li>
      <li><a href="Webpages/results.html">Results</a></li>
      <li><a href="Webpages/conclusion.html">Conclusion</a></li>
      <li><a href="Webpages/reference.html">Reference & Appendix</a></li>
    </ul>
  </div>
  <!-- End of HTML -->

  <!-- Start of Markdown -->

  <div class="top-bar">
    <a href="main.html">DS105L</a>
  </div>

  <div class="main-content">
    <h1>Title</h1>
    <p>Your main content goes here.</p>

    <h2>Subtitle</h2>
    <p>More content goes here.</p>
  </div>
  <!-- End of Markdown -->
</body>
</html>

