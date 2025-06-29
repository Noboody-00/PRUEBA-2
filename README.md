<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Rifas La Zonaja 🏍️</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fefae0;
      color: #333;
      text-align: center;
      padding: 30px;
    }

    h1 {
      color: #bc6c25;
    }

    .container {
      max-width: 600px;
      margin: auto;
      padding: 20px;
      border: 4px dashed darkkhaki;
      background-color: #fff;
      border-radius: 12px;
      text-align: left;
    }

    img {
      width: 100%;
      max-width: 400px;
      border: 4px solid darkkhaki;
      border-radius: 10px;
      margin-bottom: 20px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    .btn {
      display: inline-block;
      background-color: #bc6c25;
      color: white;
      padding: 15px 25px;
      font-size: 18px;
      text-decoration: none;
      border-radius: 8px;
      margin-top: 20px;
      text-align: center;
    }

    .btn:hover {
      background-color: #dda15e;
    }

    .marquee {
      background-color: darkkhaki;
      color: white;
      padding: 10px;
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 20px;
      text-align: center;
    }

    .info {
      margin-top: 30px;
      font-size: 16px;
      color: #555;
      line-height: 1.5;
    }

    .info strong {
      color: #bc6c25;
    }

    .info ol {
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <!-- Tira que se mueve -->
  <marquee class="marquee" behavior="scroll" direction="left">
    🎉 ¡RIFAS LA ZONAJA: PARTICIPA EN NUESTRA RIFA DE UNA MOTO NUEVA POR SOLO $50 MXN 🎉
  </marquee>

  <div class="container">
    <h1>🎉 Rifas La Zonaja: ¡Gánate una MOTO!</h1>
    <p><strong>Premio:</strong> Una motocicleta totalmente nueva 🏍️🔥</p>
    <p><strong>Costo del boleto:</strong> $50 MXN</p>
    <p><strong>Fecha del sorteo:</strong> 30 de junio de 2025</p>
    
    <img src="https://cdn.pixabay.com/photo/2017/03/30/12/40/motorbike-2180086_1280.jpg" alt="Rifa Moto">
    
    <p>¡Participa y apoya nuestros proyectos escolares! Compra tu boleto antes de que se acaben.</p>
    
    <a href="https://wa.me/5215555555555?text=Hola,%20quiero%20comprar%20un%20boleto%20para%20la%20rifa%20de%20la%20moto" target="_blank" class="btn">Comprar por WhatsApp</a>

    <div class="info">
      <h2>Información Importante</h2>
      <ol>
        <li><strong>El número GANADOR:</strong> Siempre es en base a los últimos 4 o 5 dígitos de la <em>Lotería Nacional</em>, dependiendo de la emisión. En caso de cambio de fecha de sorteo en el calendario, se recorre la rifa a la fecha de su siguiente sorteo. <strong>Nunca utilizamos otra dinámica como tómbolas, bingo, etc.</strong></li>
        <li><strong>Lista de Participantes:</strong> Publicamos la lista de todos los participantes de la rifa en nuestra página de Facebook, antes del evento.</li>
        <li><strong>Transmisión en vivo:</strong> Transmitimos en vivo por Facebook la rifa, al mismo tiempo que la Lotería Nacional, así como la entrega del premio al ganador.</li>
        <li><strong>Fecha de Rifa:</strong> El sorteo del premio mayor está sujeto a que se vendan el 80% o más de los boletos.</li>
        <li><strong>Posposición:</strong> En caso de no alcanzar el mínimo de ventas, la rifa se pospondrá por una o más semanas, respetando los boletos emitidos, apartados y vendidos.</li>
      </ol>
    </div>
  </div>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Rifas La Sonaja - Compra y Ruleta</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fefae0;
      color: #333;
      text-align: center;
      padding: 30px;
    }

    .container {
      max-width: 600px;
      margin: auto;
      padding: 20px;
      border: 4px dashed darkkhaki;
      background-color: #fff;
      border-radius: 12px;
    }

    h1 {
      color: #bc6c25;
    }

    input[type=number] {
      width: 100px;
      font-size: 18px;
      padding: 5px;
      margin-right: 10px;
      border-radius: 6px;
      border: 2px solid darkkhaki;
      text-align: center;
    }

    button {
      background-color: #bc6c25;
      color: white;
      padding: 12px 25px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin: 10px 5px;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #dda15e;
    }

    #ruletaNumero {
      font-size: 48px;
      margin: 20px 0;
      color: #bc6c25;
      font-weight: bold;
      height: 60px;
    }

    .info {
      text-align: left;
      margin-top: 30px;
      font-size: 14px;
      color: #555;
      line-height: 1.4;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>🎉 Rifas La Sonaja: ¡Compra tu boleto y gira la ruleta!</h1>
    
    <label for="boleto">Selecciona tu número (1 - 30000):</label><br/>
    <input type="number" id="boleto" min="1" max="30000" value="1" />
    <button onclick="comprarBoleto()">Comprar boleto</button>

    <hr />

    <div>
      <button onclick="girarRuleta()">🎡 Girar Ruleta</button>
      <div id="ruletaNumero">--</div>
    </div>

    <div class="info">
      <p><strong>Cómo funciona:</strong></p>
      <ol>
        <li>Escoge un número del 1 al 30000.</li>
        <li>Compra tu boleto con ese número.</li>
        <li>Gira la ruleta para seleccionar al ganador al azar.</li>
      </ol>
    </div>
  </div>

<script>
  function comprarBoleto() {
    const num = document.getElementById('boleto').value;
    if (num < 1 || num > 30000) {
      alert('Por favor, ingresa un número entre 1 y 30000.');
      return;
    }
    const url = `https://wa.me/5215555555555?text=Hola,%20quiero%20comprar%20el%20boleto%20número%20${num}%20para%20la%20rifa%20de%20la%20moto`;
    window.open(url, '_blank');
  }

  function girarRuleta() {
    const display = document.getElementById('ruletaNumero');
    let vueltas = 30; // número de cambios rápidos
    let intervalo = 50; // velocidad inicial

    let cuenta = 0;

    const intervaloId = setInterval(() => {
      const numeroAleatorio = Math.floor(Math.random() * 30000) + 1;
      display.textContent = numeroAleatorio;
      cuenta++;
      // Aumentar intervalo para simular desaceleración
      if (cuenta >= vueltas) {
        clearInterval(intervaloId);
      }
    }, intervalo);
  }
</script>

</body>
</html>

</body>
</html>


