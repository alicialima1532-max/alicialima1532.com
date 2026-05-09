# alicialima1532.com<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Convite de Aniversário - Ana & Alícia</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      min-height:100vh;
      background: linear-gradient(
        90deg,
        #000 0%,
        #111 50%,
        #8b0000 50%,
        #ff0000 100%
      );
      color:white;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:20px;
    }

    .convite{
      width:100%;
      max-width:950px;
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(10px);
      border-radius:25px;
      overflow:hidden;
      box-shadow:0 0 25px rgba(0,0,0,0.6);
      border:2px solid rgba(255,255,255,0.2);
    }

    .topo{
      display:flex;
      flex-wrap:wrap;
    }

    .lado{
      flex:1;
      min-width:300px;
      padding:30px;
      text-align:center;
    }

    .corinthians{
      background: linear-gradient(to bottom, #000, #222);
    }

    .saopaulo{
      background: linear-gradient(to bottom, #550000, #c00000);
    }

    .lado img{
      width:180px;
      max-width:90%;
      border-radius:15px;
      margin-bottom:20px;
      box-shadow:0 0 15px rgba(255,255,255,0.2);
    }

    h1{
      font-size:3rem;
      margin-bottom:10px;
      text-shadow:2px 2px 10px rgba(0,0,0,0.5);
    }

    h2{
      font-size:2rem;
      margin-bottom:15px;
    }

    .idade{
      font-size:1.4rem;
      margin-bottom:20px;
      font-weight:bold;
    }

    .info{
      padding:35px;
      text-align:center;
      background:#111;
    }

    .info p{
      margin:12px 0;
      font-size:1.2rem;
      line-height:1.6;
    }

    .destaque{
      font-size:1.4rem;
      font-weight:bold;
      color:#fff;
    }

    .kids{
      margin-top:20px;
      font-size:1.2rem;
      background:#fff;
      color:#000;
      display:inline-block;
      padding:10px 18px;
      border-radius:12px;
      font-weight:bold;
    }

    .mapa{
      margin-top:25px;
    }

    iframe{
      width:100%;
      height:300px;
      border:none;
      border-radius:18px;
    }

    .footer{
      text-align:center;
      padding:18px;
      background:#000;
      font-size:1rem;
      color:#ccc;
    }

    @media(max-width:700px){
      h1{
        font-size:2.2rem;
      }

      h2{
        font-size:1.5rem;
      }

      .info p{
        font-size:1rem;
      }
    }
  </style>
</head>

<body>

  <div class="convite">

    <div class="topo">

      <!-- Lado Corinthians -->
      <div class="lado corinthians">
        <img src="https://logodetimes.com/times/corinthians/logo-corinthians-4096.png" alt="Corinthians">
        <h2>Alícia ⚽</h2>
        <p class="idade">Corintiana 🖤🤍</p>
      </div>

      <!-- Lado São Paulo -->
      <div class="lado saopaulo">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Sao_Paulo_FC_logo.svg" alt="São Paulo">
        <h2>Ana ⚽</h2>
        <p class="idade">São Paulina ❤️🖤🤍</p>
      </div>

    </div>

    <div class="info">

      <h1>13 Anos 🎉</h1>

      <p>
        Você está convidado para o nosso almoço de aniversário!
      </p>

      <p class="destaque">
        Dia 23/05 às 12:00
      </p>

      <p>
        Nosso aniversário é dia 22/05, mas a festa será no sábado para comemorarmos juntos!
      </p>

      <p>
        📍 <strong>Local:</strong><br>
        Rua Verão, 29 - Juquehy
      </p>

      <div class="kids">
        Evento exclusivo para crianças 🎈
      </div>

      <div class="mapa">
        <iframe
          src="https://www.google.com/maps?q=Rua+Verão+29+Juquehy&output=embed"
          allowfullscreen=""
          loading="lazy">
        </iframe>
      </div>

    </div>

    <div class="footer">
      Esperamos você para comemorar com a gente! 🎂
    </div>

  </div>

</body>
</html>
