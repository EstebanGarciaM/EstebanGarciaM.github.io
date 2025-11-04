<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Esteban García Muñoz</title>
  <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
  <style>
    body {
      display: flex;
      justify-content: center;
      margin: 40px;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }
    .sidebar {
      width: 280px;
      padding-right: 30px;
      border-right: 1px solid #ddd;
    }
    .sidebar img {
      width: 100%;
      height: auto;
      display: block;
      margin-bottom: 10px;
    }
    .sidebar hr {
      border: none;
      border-top: 1px solid #ccc;
      margin: 10px 0;
    }
    .sidebar h2 {
      font-size: 1.1em;
      margin-bottom: 0;
      font-weight: bold;
    }
    .sidebar h3 {
      font-size: 1em;
      margin: 5px 0;
      font-weight: bold;
    }
    .sidebar p {
      margin: 4px 0;
    }
    .sidebar ol {
      margin-top: 10px;
      padding-left: 20px;
    }
    .sidebar a {
      color: #0366d6;
      text-decoration: none;
    }
    .sidebar a:hover {
      text-decoration: underline;
    }
    .footer {
      font-size: 0.8em;
      color: #999;
      margin-top: 20px;
    }
    .content {
      flex: 1;
      padding-left: 40px;
      max-width: 700px;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <img src="assets/foto.jpg" alt="Esteban García Muñoz">
    <hr>
    <h2>Esteban García Muñoz</h2>
    <h3>Computer Science Student</h3>
    <p><strong>(Catedrático)</strong> Professor of Computer Science and Artificial Intelligence<br>
      <a href="#">CUNEF Universidad</a> (Madrid, Spain)
    </p>
    <ol>
      <li><a href="#">Positions</a></li>
      <li><a href="#">Research</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Publications</a></li>
    </ol>
    <p><a href="#">LinkedIn</a> | email: <a href="mailto:esteban@example.com">esteban@example.com</a></p>
    <hr>
    <div class="footer">
      Hosted on GitHub Pages — Theme by orderedlist
    </div>
  </div>

  <div class="content">
    <p>
      Aquí va tu texto principal, igual que en la parte derecha de la web de tu profesor.
      Puedes copiar el texto de su web o escribir el tuyo. Esta parte es el contenido
      del perfil, experiencia, publicaciones, etc.
    </p>
  </div>
</body>
</html>
