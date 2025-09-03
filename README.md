<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Diego Mateus - Apresentação</title>
  <style>
    /* ====== Body e Fundo ====== */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 20px 0; /* espaço topo e base */
      min-height: 100vh; /* permite scroll em telas pequenas */
      display: flex;
      justify-content: center;
      align-items: flex-start; /* começa no topo */
      text-align: center;
      background: radial-gradient(circle at top, #0f2027, #09141a, #000000);
      color: #e0e0e0;
    }

    /* ====== Container ====== */
    .container {
      max-width: 800px;
      width: 90%;
      padding: 30px;
      border-radius: 15px;
      background: rgba(20, 20, 20, 0.85);
      box-shadow: 0 0 20px rgba(0, 255, 200, 0.2), 0 0 50px rgba(0, 255, 150, 0.1);
    }

    /* ====== Títulos ====== */
    h1 {
      color: #00ffc8;
      font-size: 2.2em;
    }

    h1::before {
      content: "</> ";
      color: #ff006e;
    }

    h2 {
      margin-top: 30px;
      color: #00ffc8;
      border-bottom: 1px solid #333;
      padding-bottom: 6px;
    }

    /* ====== Imagem ====== */
    img {
      margin: 60px auto 20px auto; /* desce a imagem */
      border-radius: 50%;
      max-width: 180px;
      display: block;
      border: 3px solid #00ffc8;
      box-shadow: 0 0 15px rgba(0, 255, 200, 0.4);
    }

    /* ====== Listas ====== */
    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin: 8px 0;
    }

    ul li::before {
      content: "✔️ ";
      color: #00ffc8;
    }

    .sobre li::before {
      content: "💡 ";
      color: #ffdd00;
    }

    .contato li::before {
      content: "📌 ";
      color: #00aaff;
    }

    /* ====== Links ====== */
    a {
      color: #00ffc8;
      text-decoration: none;
      transition: 0.3s;
    }

    a:hover {
      color: #ff006e;
      text-shadow: 0 0 8px #ff006e;
    }

    /* ====== Citação ====== */
    .quote {
      margin-top: 30px;
      font-style: italic;
      color: #bbb;
      font-size: 1.1em;
    }

    /* ====== Responsividade para celular ====== */
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }

      img {
        margin-top: 80px; /* desce mais a imagem */
        max-width: 150px;
      }

      h1 {
        font-size: 1.8em;
      }

      h2 {
        font-size: 1.2em;
      }

      .quote {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Olá, eu sou o Diego Mateus 👋</h1>

    <p><strong>Bacharel em Ciências da Computação</strong> • 📚 <strong>Pedagogia</strong></p>

    <img src="Diego img .jpeg" alt="Apresentação Diego Mateus">

    <h2>🎯 Áreas em que já atuei</h2>
    <ul>
      <li>Coordenação e Gestão de AVA (Moodle)</li>
      <li>Gestão Acadêmica e Pedagógica</li>
      <li>Produção de Conteúdo e Tutoria Educacional</li>
      <li>Secretaria Acadêmica</li>
      <li>Programador de Sistemas de Informação</li>
      <li>Suporte Técnico em TI (Nível I)</li>
      <li>Conhecimento prático em Banco de Dados</li>
      <li>Assistência Técnica em Eletrocomercial e Móveis</li>
      <li>Suporte Técnico Digital (Trocas, devoluções e chamados de garantia)</li>
    </ul>

    <h2>💼 Sobre mim</h2>
    <ul class="sobre">
      <li>Bacharel em Ciências da Computação</li>
      <li>Pedagogia</li>
      <li>Atuação em apoio pedagógico, orientação acadêmica e suporte tecnológico</li>
    </ul>

    <h2>📞 Contato</h2>
    <ul class="contato">
      <li>WhatsApp: <a href="https://wa.me/5533984515507?text=Olá%20Diego,%20vim%20pelo%20GitHub!" target="_blank">Clique aqui</a></li>
      <li>E-mail: <a href="mailto:diego.profissional37@outlook.com">diego.profissional37@outlook.com</a></li>
    </ul>

    <p class="quote">“Ensinar é transformar conhecimento em oportunidade.”</p>
  </div>
</body>
</html>
