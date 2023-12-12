<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Learning Node.js - Basic Informational Site</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      margin: 20px;
    }

    h1, h2, h3 {
      color: #333;
    }

    code {
      background-color: #f4f4f4;
      padding: 2px 4px;
      border: 1px solid #ddd;
    }

    pre {
      background-color: #f8f8f8;
      padding: 10px;
      border: 1px solid #ddd;
      overflow: auto;
    }

    a {
      color: #4078c0;
    }

    ul {
      list-style-type: disc;
    }

    li {
      margin-bottom: 5px;
    }

    hr {
      border: 1px solid #ddd;
      margin-top: 20px;
      margin-bottom: 30px;
    }
  </style>
</head>
<body>

  <h1>Learning Node.js - Basic Informational Site</h1>

  <p>
    Project: Basic Informational Site
  </p>

  <h2>Project Structure</h2>

  <p>
    1. Make a project directory and create the following files inside that directory:
  </p>

  <ul>
    <li><code>index.html</code></li>
    <li><code>about.html</code></li>
    <li><code>contact-me.html</code></li>
    <li><code>404.html</code></li>
  </ul>

  <p>
    2. Create your Node.js server file <code>index.js</code> and add the code needed to serve the right page according to the URL.
  </p>

  <ul>
    <li><code>localhost:8080</code> should take users to <code>index.html</code></li>
    <li><code>localhost:8080/about</code> should take users to <code>about.html</code></li>
    <li><code>localhost:8080/contact-me</code> should take users to <code>contact-me.html</code></li>
    <li><code>404.html</code> should display any time the user tries to go to a page not listed above.</li>
  </ul>

</body>
</html>

