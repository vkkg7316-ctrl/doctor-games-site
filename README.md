<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DoctorGames.com - Conserto de Celulares e Video Games</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }

    header {
      background-color: #111;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .services {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    .service {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    .service img {
      width: 100px;
      height: auto;
      margin-bottom: 15px;
    }

    .whatsapp {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 40px;
    }

    .whatsapp a {
      background-color: #25d366;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-size: 18px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .whatsapp a:hover {
      background-color: #20b358;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      color: #fff;
      margin-top: 40px;
    }

    @media(max-width: 768px) {
      .services {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>DoctorGames.com</h1>
  <p>Especialistas em Conserto de Celulares e Video Games</p>
</header>

<section>
  <h2 style="text-align:center;">Nossos Serviços</h2>
  <div class="services">
    <div class="service">
      <img src="https://cdn-icons-png.flaticon.com/512/3405/3405846.png" alt="Celular" />
      <h3>Reparo de Celulares</h3>
      <p>Troca de tela, bateria, conector de carga e muito mais.</p>
    </div>
    <div class="service">
      <img src="https://cdn-icons-png.flaticon.com/512/831/831276.png" alt="Videogame" />
      <h3>Manutenção de Video Games</h3>
      <p>Limpeza, troca de pasta térmica, troca de peças e reparos gerais.</p>
    </div>
  </div>

  <div class="whatsapp">
    <a href="https://wa.me/5543996961389" target="_blank" rel="noopener noreferrer">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" width="24" />
      Entrar em Contato: +55 (43) 99696-1389
    </a>
  </div>
</section>

<footer>
  &copy; 2025 DoctorGames.com - Todos os direitos reservados.
</footer>

</body>
</html>
