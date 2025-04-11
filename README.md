<!doctype html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Brasileiros estão lucrando com método caseiro</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #fafafa;
        margin: 0;
        padding: 0;
      }
      .container {
        max-width: 700px;
        margin: 40px auto;
        background: white;
        padding: 30px;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      }
      h1,
      h3 {
        color: #2c3e50;
      }
      p {
        line-height: 1.6;
        color: #333;
      }
      .img {
        text-align: center;
        margin: 20px 0;
      }
      .img img {
        max-width: 100%;
        border-radius: 10px;
      }
      .cta {
        text-align: center;
        margin-top: 30px;
      }
      .cta a {
        padding: 15px 30px;
        background-color: #2ecc71;
        color: white;
        font-size: 18px;
        border-radius: 8px;
        text-decoration: none;
        animation: pulse 1.5s infinite;
        display: inline-block;
      }
      @keyframes pulse {
        0% {
          transform: scale(1);
        }
        50% {
          transform: scale(1.05);
        }
        100% {
          transform: scale(1);
        }
      }
      .alert {
        margin-top: 20px;
        font-size: 12px;
        color: #999;
        text-align: center;
      }
      .comments {
        margin-top: 50px;
        border-top: 1px solid #eee;
        padding-top: 20px;
      }
      .comment {
        margin-bottom: 15px;
      }
      .comment strong {
        color: #2c3e50;
      }
      .counter-box {
        background: #ffeaa7;
        padding: 10px;
        margin: 20px 0;
        text-align: center;
        font-size: 16px;
        border-radius: 5px;
        color: #d63031;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>
        Brasileiros estão ganhando até R$300 por dia com método simples e
        desconhecido
      </h1>

      <div class="img">
        <img
          src="https://i.postimg.cc/G2Bg5zJH/3b7345177ba7171acb95087daa56a3d7.jpg"
          alt="Pix Recebido"
        />
        <p>
          <em
            >"Sthephany, de SP, mostra o que recebeu em um único dia com o
            método."</em
          >
        </p>
      </div>

      <p>
        Um novo método tem chamado atenção de milhares de brasileiros que estão
        cansados de viver no aperto. Com apenas um celular e acesso à internet,
        pessoas estão gerando renda extra todos os dias, sem precisar sair de
        casa.
      </p>

      <p>
        O que antes parecia impossível, agora se tornou realidade graças a uma
        nova ferramenta que ensina passo a passo como ganhar dinheiro online, de
        forma honesta e rápida.
      </p>

      <h3>“No primeiro dia já caiu R$124 no meu Pix”</h3>

      <p>
        É o que conta <strong>Letícia, de Recife</strong>, que estava
        desempregada há 6 meses e começou a testar o método em seu tempo livre.
        “Eu pensei que fosse golpe, mas no mesmo dia que comecei, já vi o
        dinheiro cair. Agora faço R$200 por dia em média”, conta.
      </p>

      <h3>Como funciona?</h3>

      <p>
        O sistema ensina como realizar tarefas simples pela internet, como
        assistir vídeos, clicar em anúncios e responder pesquisas. Quanto mais
        tempo você dedica, maior o retorno.
      </p>

      <p>
        <strong
          >Não precisa vender nada, não precisa aparecer e é totalmente
          legal.</strong
        >
      </p>

      <div class="counter-box">
        ⚠️ Apenas <span id="counter">17</span> vagas disponíveis!
      </div>

      <h3>Quer começar agora?</h3>

      <p>
        Devido ao sucesso, as vagas para acesso ao método são limitadas. Clique
        no botão abaixo e veja como começar ainda hoje:
      </p>

      <div class="cta">
        <a href="https://pay.kirvano.com/9934c64a-cfe0-440b-8354-435b811b9065?aff=df8a7781-ff26-4265-a4ac-9af1be4161b2" target="_blank"
          >🔓 ACESSAR O MÉTODO AGORA</a
        >
      </div>

      <div class="alert">
        *Vagas limitadas. Atualizado hoje às <span id="hora"></span>.
      </div>

      <div class="comments">
        <h3>Comentários:</h3>
        <div class="comment">
          <strong>Ana Souza:</strong> Gente, acabei de receber meu primeiro Pix!
          🙏 Obrigada!
        </div>
        <div class="comment">
          <strong>Jorge L.:</strong> Tava desconfiado, mas testei e FUNCIONA!
        </div>
        <div class="comment">
          <strong>Paulo Henrique:</strong> Indiquei pra minha mãe, ela tá
          viciada rsrs
        </div>
      </div>
    </div>

    <script>
      // Contador fake de vagas (diminui de tempo em tempo)
      let vagas = 17
      const spanCounter = document.getElementById("counter")
      setInterval(() => {
        if (vagas > 6) {
          vagas--
          spanCounter.textContent = vagas
        }
      }, 8000)

      // Hora atual fake
      const hora = new Date()
      document.getElementById("hora").textContent = hora
        .toLocaleTimeString("pt-BR")
        .slice(0, 5)
    </script>
  </body>
</html>
