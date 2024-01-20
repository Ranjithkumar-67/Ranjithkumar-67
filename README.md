<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Combined Example</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)), url('https://images.unsplash.com/photo-1519296909669-06b04833958f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
      background-position: center;
      background-size: cover;
    }

    header {
      background-color: #359bd5;
      color: #c6426e;
      padding: 10px;
      text-align: center;
    }

    .grid-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 10px;
      justify-content: space-around;
      padding: 20px;
    }

    .grid-item {
      border: 1px solid #333;
      padding: 20px;
      text-align: center;
    }

    .item {
      flex: 1;
      min-width: 250px;
      max-width: 400px;
      margin: 10px;
      padding: 20px;
      border: 1px solid #000000;
      border-radius: 5px;
      background-color: #f8f8f8;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .item:hover {
      background-color: #8e27ad;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>

<body>
  <header>
    <h1>HTML & CSS GRID</h1>
  </header>

  <main class="grid-container">
    <!-- Grid items -->
    <div class="grid-item">1</div>
    <div class="grid-item">2</div>
    <div class="grid-item">3</div>
    <div class="grid-item">4</div>
    <div class="grid-item">5</div>
    <div class="grid-item">6</div>
  </main>

  <footer>
    <p>Footer</p>
  </footer>
</body>
</html>
