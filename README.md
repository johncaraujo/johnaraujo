<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Transforme Sua Vida com Hipnose</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #1a1a1a;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .cta-button {
      background-color: #ffcc00; /* Amarelo queimado */
      color: #1a1a1a;
      border: none;
      padding: 15px 30px;
      font-size: 1.2rem;
      cursor: pointer;
      border-radius: 5px;
      text-transform: uppercase;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #e6b800; /* Hover mais escuro */
    }

    .form-container {
      background-color: #fff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 40px;
      margin: 30px auto;
      border-radius: 10px;
      max-width: 400px;
    }

    .form-container input, .form-container button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    .form-container input:focus, .form-container button:focus {
      border-color: #ffcc00;
      outline: none;
    }

    .form-container button {
      background-color: #ffcc00;
      color: #1a1a1a;
      font-size: 1.2rem;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s ease;
    }

    .form-container button:hover {
      background-color: #e6b800;
    }

    .benefits, .testimonials {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
    }

    .benefit, .testimonial {
      background-color: #fff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px;
      margin: 15px;
      width: 250px;
      border-radius: 10px;
    }

    .benefit h3, .testimonial h3 {
      font-size: 1.4rem;
      margin-bottom: 15px;
    }

    footer {
      background-color: #1a1a1a;
      color: #fff;
      text-align: center;
      padding: 20px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }

    footer a {
      color: #ffcc00;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <header>
    <h1>Transforme Sua Vida com a Hipnose</h1>
    <p>Descubra como o poder da mente pode mudar sua realidade. Baixe gratuitamente o nosso eBook e comece agora!</p>
  </header>

  <!-- Seção de Introdução -->
  <section>
    <h2>O que a hipnose pode fazer por você?</h2>
    <p>Alívio do estresse, aumento da confiança e transformação positiva. Comece sua jornada de autodescoberta agora!</p>
    <button class="cta-button" onclick="document.getElementById('download-form').scrollIntoView();">Baixar o Material</button>
  </section>

  <!-- Benefícios -->
  <section>
    <h2>Benefícios da Hipnose</h2>
    <div class="benefits">
      <div class="benefit">
        <h3>Alívio do Estresse</h3>
        <p>Libere-se do estresse diário e encontre equilíbrio na sua vida.</p>
      </div>
      <div class="benefit">
        <h3>Melhoria no Sono</h3>
        <p>Durma melhor e acorde mais disposto para enfrentar o dia.</p>
      </div>
      <div class="benefit">
        <h3>Superação de Medos</h3>
        <p>Supere suas fobias e medos com sessões de hipnose poderosas.</p>
      </div>
    </div>
  </section>

  <!-- Depoimentos -->
  <section>
    <h2>O Que Nossos Clientes Dizem</h2>
    <div class="testimonials">
      <div class="testimonial">
        <h3>Joana R.</h3>
        <p>"A hipnose me ajudou a superar meu medo de falar em público. Sou muito mais confiante agora!"</p>
      </div>
      <div class="testimonial">
        <h3>Carlos M.</h3>
        <p>"Após a palestra, consegui dormir melhor e a ansiedade diminuiu muito. Gratidão!"</p>
      </div>
      <div class="testimonial">
        <h3>Renata S.</h3>
        <p>"Fiquei impressionada com os resultados da minha primeira sessão de hipnose. Recomendo a todos!"</p>
      </div>
    </div>
  </section>

  <!-- Formulário para Captura do eBook -->
  <section id="download-form">
    <div class="form-container">
      <h2>Baixe Seu eBook Agora!</h2>
      <p>Preencha os dados abaixo e receba o material no seu e-mail.</p>
      <form action="mailto:seu-email@dominio.com" method="POST" enctype="multipart/form-data">
        <input type="text" name="nome" placeholder="Nome Completo" required>
        <input type="email" name="email" placeholder="Digite seu e-mail" required>
        <input type="tel" name="telefone" placeholder="Telefone (opcional)" required>
        <button type="submit">Baixar eBook</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>© 2025 Hipnose Transformadora | <a href="#">Termos e Condições</a></p>
    <p>Siga-nos nas redes sociais: <a href="#">Instagram</a>, <a href="#">Facebook</a></p>
  </footer>

</body>
</html>
