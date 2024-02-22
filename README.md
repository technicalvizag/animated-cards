<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Animated Cards</title>
<style>
  body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
  }

  .card {
    width: 200px;
    height: 300px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    margin: 20px;
  }

  .card:hover {
    transform: translateY(-10px);
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .card-content {
    padding: 20px;
    text-align: center;
  }

  h2 {
    margin-top: 0;
  }
</style>
</head>
<body>

<div class="container">
  <div class="card">
    <div class="card-content">
      <h2>Card 1</h2>
      <p>This is the content of card 1.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-content">
      <h2>Card 2</h2>
      <p>This is the content of card 2.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-content">
      <h2>Card 3</h2>
      <p>This is the content of card 3.</p>
    </div>
  </div>
</div>

</body>
</html>
