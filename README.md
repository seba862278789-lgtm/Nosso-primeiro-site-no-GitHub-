# Nosso-primeiro-site-no-GitHub-
Nosso primeiro site no GitHub <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurante Sabor & Tradição</title>
  <meta name="description" content="Restaurante Sabor & Tradição — criado pelos chefs Edmilson Emílio Jamal, Emir Alberto e Mateus. Comida com alma, sabor e tradição.">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fffaf2;
      color: #333;
    }

    header {
      background-image: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1400&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 80px 10px;
      position: relative;
    }

    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0,0,0,0.5);
    }

    header h1, header p {
      position: relative;
      z-index: 1;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    nav {
      background-color: #b22222;
      text-align: center;
      padding: 12px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .sobre {
      text-align: center;
      padding: 40px 10px;
    }

    .sobre h2 {
      color: #b22222;
      font-size: 1.8em;
    }

    .chefs {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .chef {
      background: white;
      border-radius: 10px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      padding: 15px;
      width: 250px;
      text-align: center;
    }

    .chef img {
      width: 100%;
      border-radius: 10px;
    }

    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 30px 0;
    }

    .prato {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }

    .prato img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      background-color: #b22222;
      color: white;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9em;
    }

    .nomes {
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>🍴 Restaurante Sabor & Tradição</h1>
    <p>Comida feita com alma, sabor e amizade!</p>
  </header>

  <nav>
    <a href="#sobre">Sobre Nós</a>
    <a href="#menu">Cardápio</a>
    <a href="#contato">Contato</a>
  </nav>

  <div class="container">
    <section id="sobre" class="sobre">
      <h2>Sobre Nós</h2>
      <p>
        O <strong>Restaurante Sabor & Tradição</strong> nasceu do sonho de três amigos apaixonados por gastronomia:
      </p>

      <div class="chefs">
        <div class="chef">
          <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=600&q=60" alt="Edmilson Emílio Jamal">
          <h3>👨🏾‍🍳 Edmilson Emílio Jamal</h3>
          <p>Especialista em grelhados e carnes com sabor autêntico.</p>
        </div>

        <div class="chef">
          <img src="https://images.unsplash.com/photo-1551218808-94e220e084d2?auto=format&fit=crop&w=600&q=60" alt="Emir Alberto">
          <h3>👨🏽‍🍳 Emir Alberto</h3>
          <p>Mestre das massas e molhos, trazendo um toque italiano à mesa.</p>
        </div>

        <div class="chef">
          <img src="https://images.unsplash.com/photo-1528715471579-d1bcf0ba5e83?auto=format&fit=crop&w=600&q=60" alt="Mateus">
          <h3>👨🏽‍🍳 Mateus</h3>
          <p>Responsável pelas sobremesas irresistíveis e pelo toque final.</p>
        </div>
      </div>
    </section>

    <section id="menu">
      <h2 style="text-align:center; color:#b22222;">Nosso Cardápio</h2>
      <div class="menu">
        <div class="prato">
          <img src="https://images.unsplash.com/photo-1601924579440-28eebeb3192b?auto=format&fit=crop&w=800&q=60" alt="Churrasco">
          <h3>Churrasco da Casa</h3>
          <p>Carne suculenta preparada no ponto perfeito com tempero exclusivo.</p>
        </div>

        <div class="prato">
          <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f?auto=format&fit=crop&w=800&q=60" alt="Massas Artesanais">
          <h3>Massas Artesanais</h3>
          <p>Feitas à mão com molhos especiais de Emir Alberto.</p>
        </div>

        <div class="prato">
          <img src="https://images.unsplash.com/photo-1617196039897-64a3c16f7b90?auto=format&fit=crop&w=800&q=60" alt="Sobremesas">
          <h3>Sobremesas Especiais</h3>
          <p>Doces preparados por Mateus com um toque de amor e tradição.</p>
        </div>
      </div>
    </section>

    <section id="contato" class="sobre">
      <h2>Contato</h2>
      <p>📍 Rua do Sabor, nº 123 — Cidade Gourmet</p>
      <p>📞 (99) 99999-9999</p>
      <p>📧 contato@saboretradicao.com</p>
    </section>
  </div>

  <footer>
    <p>© 2025 Restaurante Sabor & Tradição</p>
    <p class="nomes">Criado por: <br>
    👨🏾‍🍳 <strong>Edmilson Emílio Jamal</strong> | 👨🏽‍🍳 <strong>Emir Alberto</strong> | 👨🏽‍🍳 <strong>Mateus</strong></p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurante Sabor & Tradição</title>
  <meta name="description" content="Restaurante Sabor & Tradição — qualidade, sabor e um toque especial dos chefs Edmilson Emílio Jamal, Emir Alberto e Mateus.">
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background-color: #fffaf2;
      color: #333;
    }

    header {
      background-color: #b22222;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
      letter-spacing: 1px;
    }

    nav {
      background-color: #8b0000;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .sobre {
      text-align: center;
      padding: 30px 0;
    }

    .sobre h2 {
      color: #b22222;
    }

    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px 0;
    }

    .prato {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }

    .prato img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      background-color: #b22222;
      color: white;
      text-align: center;
      padding: 15px 5px;
      font-size: 0.9em;
    }

    .nomes {
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>🍽️ Restaurante Sabor & Tradição</h1>
    <p>Onde cada refeição é feita com amor e tradição!</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#menu">Cardápio</a>
    <a href="#contato">Contato</a>
  </nav>

  <div class="container">
    <section id="sobre" class="sobre">
      <h2>Sobre Nós</h2>
      <p>O <strong>Restaurante Sabor & Tradição</strong> é fruto da paixão pela gastronomia de três grandes amigos e chefs: <br>
      <strong>Edmilson Emílio Jamal</strong>, <strong>Emir Alberto</strong> e <strong>Mateus</strong>. <br><br>
      Juntos, criamos um espaço onde o sabor caseiro se une à excelência da cozinha moderna.</p>
    </section>

    <section id="menu">
      <h2 style="text-align:center; color:#b22222;">Nosso Cardápio</h2>
      <div class="menu">
        <div class="prato">
          <img src="https://images.unsplash.com/photo-1601924579440-28eebeb3192b?auto=format&fit=crop&w=800&q=60" alt="Prato de carne">
          <h3>Churrasco da Casa</h3>
          <p>Suculentas carnes grelhadas com temperos secretos dos nossos chefs.</p>
        </div>
        <div class="prato">
          <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f?auto=format&fit=crop&w=800&q=60" alt="Massa">
          <h3>Massas Artesanais</h3>
          <p>Preparadas com ingredientes frescos e molho feito na hora.</p>
        </div>
        <div class="prato">
          <img src="https://images.unsplash.com/photo-1617196039897-64a3c16f7b90?auto=format&fit=crop&w=800&q=60" alt="Sobremesa">
          <h3>Sobremesas Especiais</h3>
          <p>Doces caseiros e sobremesas irresistíveis para encerrar com chave de ouro.</p>
        </div>
      </div>
    </section>

    <section id="contato" class="sobre">
      <h2>Contato</h2>
      <p>📍 Localização: Rua do Sabor, nº 123 – Cidade Gourmet</p>
      <p>📞 Telefone: (99) 99999-9999</p>
      <p>📧 Email: contato@saboretradicao.com</p>
    </section>
  </div>

  <footer>
    <p>© 2025 Restaurante Sabor & Tradição</p>
    <p class="nomes">Criado por: Edmilson Emílio Jamal | Emir Alberto | Mateus</p>
  </footer>

</body>
</html>
