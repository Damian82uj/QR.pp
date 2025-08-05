
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>QR PRO - Sistema Avanzado 2025</title>
  <style>
    :root {
      --primary: #1565c0;
      --accent: #00bfa5;
      --light-bg: #f0f8ff;
      --card-bg: #ffffff;
      --text-dark: #1a1a1a;
      --soft-shadow: 0 10px 30px rgba(0,0,0,0.08);
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: radial-gradient(circle at top left, var(--light-bg), #ffffff);
      color: var(--text-dark);
    }

    header {
      background: linear-gradient(90deg, var(--primary), #1e88e5);
      padding: 30px 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 2.2em;
    }

    .main {
      max-width: 960px;
      margin: auto;
      padding: 30px 20px;
    }

    .form-section {
      background: var(--card-bg);
      border-radius: 20px;
      box-shadow: var(--soft-shadow);
      padding: 25px;
      margin-bottom: 40px;
    }

    .form-section label {
      display: block;
      font-size: 1em;
      margin-bottom: 8px;
      color: #333;
    }

    input[type="text"] {
      width: 100%;
      padding: 14px;
      font-size: 1em;
      border: 2px solid #bbdefb;
      border-radius: 12px;
      margin-bottom: 20px;
    }

    button {
      background: linear-gradient(90deg, var(--accent), #00796b);
      color: white;
      border: none;
      padding: 14px 20px;
      font-size: 1em;
      border-radius: 12px;
      cursor: pointer;
      transition: background 0.3s ease;
      width: 100%;
    }

    button:hover {
      background: linear-gradient(90deg, #00796b, var(--accent));
    }

    .qr-section {
      margin-top: 30px;
    }

    .qr-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
    }

    .qr-card {
      background: white;
      border-radius: 18px;
      box-shadow: var(--soft-shadow);
      padding: 15px;
      text-align: center;
      transition: transform 0.2s;
    }

    .qr-card:hover {
      transform: scale(1.02);
    }

    .qr-card img {
      width: 160px;
      height: 160px;
      margin-bottom: 10px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }

    .qr-link {
      font-size: 0.9em;
      word-break: break-word;
      color: var(--primary);
      margin-bottom: 10px;
    }

    .qr-card button {
      background-color: var(--primary);
      border: none;
      padding: 10px 16px;
      color: white;
      border-radius: 8px;
      font-size: 0.9em;
    }

    .pasos {
      margin-top: 50px;
      background: #e8f5e9;
      border-left: 6px solid var(--accent);
      border-radius: 12px;
      padding: 20px;
      font-size: 1em;
      color: #2e7d32;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }

    .footer {
      text-align: center;
      margin-top: 60px;
      padding: 20px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>QR PRO 2025</h1>
    <p style="margin:0;">Generador de QR visual elegante con registro automático</p>
  </header>

  <div class="main">
    <div class="form-section">
      <label for="inputLink">🌐 Escribí tu dominio o enlace:</label>
      <input type="text" id="inputLink" placeholder="https://miempresa.com/evento" />
      <button onclick="generarQR()">Generar y Registrar</button>
    </div>

    <div class="qr-section">
      <h2 style="color:#333; margin-bottom: 10px;">🗂 QR Registrados</h2>
      <div class="qr-grid" id="qrLista"></div>
    </div>

    <div class="pasos">
      <strong>📌 ¿Cómo funciona?</strong><br>
      ✅ Ingresá tu dominio o link personalizado.<br>
      ✅ Tocá “Generar y Registrar” y el QR se crea arriba.<br>
      ✅ Cada QR tiene su botón de descarga.<br>
      ✅ Se guardan automáticamente sin borrar ninguno.
    </div>

    <div class="footer">© QR PRO 2025 | Todos los derechos reservados</div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/qrcode/build/qrcode.min.js"></script>
  <script>
    const qrLista = document.getElementById('qrLista');

    function generarQR() {
      const enlace = document.getElementById('inputLink').value.trim();
      if (!enlace) {
        alert("Por favor ingresá un enlace válido.");
        return;
      }

      QRCode.toDataURL(enlace, { width: 160, margin: 1 }, function (err, url) {
        if (err) return console.error(err);

        const tarjeta = document.createElement('div');
        tarjeta.className = 'qr-card';

        const img = document.createElement('img');
        img.src = url;

        const texto = document.createElement('div');
        texto.className = 'qr-link';
        texto.textContent = enlace;

        const btn = document.createElement('button');
        btn.textContent = "Descargar QR";
        btn.onclick = function () {
          const a = document.createElement('a');
          a.href = url;
          a.download = "qr_registrado.png";
          document.body.appendChild(a);
          a.click();
          document.body.removeChild(a);
        };

        tarjeta.appendChild(img);
        tarjeta.appendChild(texto);
        tarjeta.appendChild(btn);
        qrLista.prepend(tarjeta);
      });
    }
  </script>

</body>
</html>
