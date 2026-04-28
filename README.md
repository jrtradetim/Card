<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Download</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      font-family: Arial, sans-serif;
      color: white;
    }

    .container {
      text-align: center;
    }

    h1 {
      margin-bottom: 20px;
      font-size: 2rem;
    }

    .btn {
      background: #00c6ff;
      background: linear-gradient(45deg, #0072ff, #00c6ff);
      padding: 15px 30px;
      border-radius: 30px;
      color: white;
      text-decoration: none;
      font-size: 18px;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px rgba(0,198,255,0.6);
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Baixe seu arquivo</h1>
    <a href="arquivo.pdf" download class="btn">📥 Baixar Agora</a>
  </div>

</body>
</html>
