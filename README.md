
<html lang="es"
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>QR VIRAL PRO - Sistema Premium 2025</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary: #6a11cb;
      --accent: #2575fc;
      --light-bg: #f8f9fa;
      --card-bg: #ffffff;
      --text-dark: #1a1a1a;
      --soft-shadow: 0 10px 30px rgba(0,0,0,0.08);
      --qr-color: #000000;
      --qr-bg-color: #ffffff;
      --gold: #ffd700;
      --silver: #c0c0c0;
      --premium-gradient: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      --viral-gradient: linear-gradient(135deg, #ff6b6b 0%, #ffa500 100%);
    }

    * {
      box-sizing: border-box;
      transition: all 0.3s ease;
    }

    body {
      font-family: 'Poppins', 'Segoe UI', sans-serif;
      margin: 0;
      background: radial-gradient(circle at top left, var(--light-bg), #ffffff);
      color: var(--text-dark);
      min-height: 100vh;
    }

    header {
      background: var(--viral-gradient);
      padding: 40px 20px;
      text-align: center;
      color: white;
      position: relative;
      overflow: hidden;
      box-shadow: 0 6px 25px rgba(255, 107, 107, 0.3);
    }

    header::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,255,255,0.15) 0%, transparent 70%);
      transform: rotate(30deg);
    }

    .premium-badge {
      position: absolute;
      top: 20px;
      right: 20px;
      background: var(--gold);
      color: #000;
      padding: 8px 15px;
      border-radius: 25px;
      font-size: 0.9em;
      font-weight: bold;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      display: flex;
      align-items: center;
      gap: 8px;
    }

    header h1 {
      margin: 0;
      font-size: 3.2em;
      font-weight: 800;
      text-shadow: 0 3px 6px rgba(0,0,0,0.2);
      position: relative;
      letter-spacing: 1px;
    }

    header p {
      margin: 15px 0 0;
      font-size: 1.3em;
      opacity: 0.95;
      position: relative;
      font-weight: 300;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    .main {
      max-width: 1200px;
      margin: auto;
      padding: 50px 20px;
    }

    .panel-configuracion {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      margin-bottom: 50px;
    }

    .form-section {
      flex: 2;
      min-width: 350px;
      background: var(--card-bg);
      border-radius: 25px;
      box-shadow: var(--soft-shadow);
      padding: 35px;
      position: relative;
      overflow: hidden;
    }

    .form-section::after {
      content: '';
      position: absolute;
      top: 0;
      right: 0;
      width: 100%;
      height: 6px;
      background: var(--viral-gradient);
    }

    .style-section {
      flex: 1;
      min-width: 300px;
      background: var(--card-bg);
      border-radius: 25px;
      box-shadow: var(--soft-shadow);
      padding: 35px;
      position: relative;
      overflow: hidden;
    }

    .style-section::after {
      content: '';
      position: absolute;
      top: 0;
      right: 0;
      width: 100%;
      height: 6px;
      background: var(--viral-gradient);
    }

    .section-title {
      display: flex;
      align-items: center;
      gap: 15px;
      margin-bottom: 25px;
      color: #444;
      font-weight: 700;
      font-size: 1.4em;
    }

    .section-title i {
      background: var(--viral-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-size: 1.5em;
    }

    .form-section label, .style-section label {
      display: block;
      font-size: 1.1em;
      margin-bottom: 12px;
      color: #555;
      font-weight: 600;
    }

    input[type="text"] {
      width: 100%;
      padding: 18px;
      font-size: 1.1em;
      border: 2px solid #e0e0e0;
      border-radius: 15px;
      margin-bottom: 30px;
      font-family: inherit;
      transition: all 0.3s;
    }

    input[type="text"]:focus {
      border-color: #ff6b6b;
      box-shadow: 0 0 0 4px rgba(255, 107, 107, 0.2);
      outline: none;
    }

    .color-section {
      margin-bottom: 30px;
    }

    .color-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 15px;
    }

    .color-title {
      font-size: 1.1em;
      font-weight: 600;
      color: #555;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .reset-colors {
      background: #f5f5f5;
      color: #666;
      border: none;
      padding: 8px 15px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 500;
      transition: all 0.3s;
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 0.9em;
    }

    .reset-colors:hover {
      background: #eaeaea;
      color: #333;
    }

    .color-picker-container {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 20px;
    }

    .color-picker {
      position: relative;
      text-align: center;
    }

    .color-label {
      display: block;
      margin-bottom: 12px;
      font-weight: 600;
      color: #666;
      text-align: center;
    }

    input[type="color"] {
      width: 100%;
      height: 60px;
      border: 3px solid #f0f0f0;
      border-radius: 15px;
      cursor: pointer;
      margin-bottom: 10px;
      padding: 3px;
      background: white;
      transition: all 0.3s;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    }

    input[type="color"]:hover {
      border-color: #ff6b6b;
      transform: scale(1.03);
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .color-hex {
      font-size: 0.9em;
      color: #777;
      font-weight: 500;
    }

    .preset-colors {
      margin-top: 25px;
    }

    .preset-title {
      font-size: 1.1em;
      font-weight: 600;
      color: #555;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .color-presets {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
    }

    .color-preset {
      height: 40px;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      position: relative;
    }

    .color-preset:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    }

    .color-preset.active {
      transform: scale(1.05);
      box-shadow: 0 0 0 3px white, 0 0 0 6px #ff6b6b;
    }

    button.generate-btn {
      background: var(--viral-gradient);
      color: white;
      border: none;
      padding: 20px 30px;
      font-size: 1.2em;
      border-radius: 15px;
      cursor: pointer;
      transition: all 0.3s ease;
      width: 100%;
      font-weight: 700;
      box-shadow: 0 8px 20px rgba(255, 107, 107, 0.4);
      position: relative;
      overflow: hidden;
      margin-top: 10px;
    }

    button.generate-btn::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
      transition: all 0.6s ease;
    }

    button.generate-btn:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(255, 107, 107, 0.5);
    }

    button.generate-btn:hover::before {
      left: 100%;
    }

    button.generate-btn:active {
      transform: translateY(0);
    }

    .qr-section {
      margin-top: 50px;
    }

    .section-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 30px;
    }

    .section-header h2 {
      color: #333;
      margin: 0;
      font-size: 2em;
      font-weight: 800;
      display: flex;
      align-items: center;
      gap: 15px;
      background: var(--viral-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .clear-button {
      background: #f5f5f5;
      color: #666;
      border: none;
      padding: 12px 24px;
      border-radius: 10px;
      cursor: pointer;
      font-weight: 600;
      transition: all 0.3s;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .clear-button:hover {
      background: #eaeaea;
      color: #333;
    }

    .qr-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 30px;
    }

    .qr-card {
      background: white;
      border-radius: 20px;
      box-shadow: var(--soft-shadow);
      padding: 25px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
      position: relative;
      overflow: hidden;
      border: 1px solid #f0f0f0;
    }

    .qr-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 6px;
      background: var(--viral-gradient);
    }

    .qr-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.12);
    }

    .delete-btn {
      position: absolute;
      top: 15px;
      right: 15px;
      background: #ff4757;
      color: white;
      border: none;
      width: 35px;
      height: 35px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      opacity: 0.8;
      transition: all 0.3s;
      z-index: 10;
      box-shadow: 0 4px 10px rgba(255, 71, 87, 0.3);
    }

    .delete-btn:hover {
      opacity: 1;
      transform: scale(1.1);
    }

    .qr-image-container {
      padding: 20px;
      margin-bottom: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .qr-card img {
      width: 200px;
      height: 200px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      object-fit: contain;
    }

    .qr-link {
      font-size: 1em;
      word-break: break-word;
      color: #555;
      margin-bottom: 25px;
      padding: 0 15px;
      line-height: 1.5;
      font-weight: 500;
    }

    .qr-actions {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    .qr-card button {
      background: var(--viral-gradient);
      border: none;
      padding: 14px 24px;
      color: white;
      border-radius: 12px;
      font-size: 1em;
      margin-top: 5px;
      width: auto;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      box-shadow: 0 5px 15px rgba(255, 107, 107, 0.3);
      font-weight: 600;
    }

    .qr-card button:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(255, 107, 107, 0.4);
    }

    .qr-card button.secondary {
      background: #f5f5f5;
      color: #666;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .qr-card button.secondary:hover {
      background: #eaeaea;
      color: #333;
    }

    .pasos {
      margin-top: 70px;
      background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
      border-left: 6px solid #4caf50;
      border-radius: 18px;
      padding: 35px;
      font-size: 1.1em;
      color: #2e7d32;
      box-shadow: 0 8px 20px rgba(0,0,0,0.06);
      line-height: 1.6;
    }

    .pasos strong {
      font-size: 1.3em;
      display: block;
      margin-bottom: 20px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .footer {
      text-align: center;
      margin-top: 90px;
      padding: 35px;
      font-size: 1em;
      color: #777;
      border-top: 1px solid #eee;
    }

    @media (max-width: 968px) {
      .panel-configuracion {
        flex-direction: column;
      }
      
      .color-picker-container {
        grid-template-columns: 1fr;
      }
      
      .color-presets {
        grid-template-columns: repeat(4, 1fr);
      }
    }

    @media (max-width: 768px) {
      .qr-grid {
        grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      }
      
      header h1 {
        font-size: 2.5em;
      }
      
      .color-presets {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 480px) {
      .qr-grid {
        grid-template-columns: 1fr;
      }
      
      .color-presets {
        grid-template-columns: repeat(2, 1fr);
      }
      
      .section-header {
        flex-direction: column;
        gap: 15px;
        align-items: flex-start;
      }
    }

    .toast {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: var(--viral-gradient);
      color: white;
      padding: 18px 26px;
      border-radius: 14px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.3s ease;
      z-index: 1000;
      display: flex;
      align-items: center;
      gap: 12px;
      font-weight: 500;
    }

    .toast.show {
      opacity: 1;
      transform: translateY(0);
    }

    .empty-state {
      text-align: center;
      padding: 70px 20px;
      color: #888;
    }

    .empty-state i {
      font-size: 5em;
      margin-bottom: 25px;
      opacity: 0.3;
    }

    .empty-state p {
      font-size: 1.3em;
      margin: 0;
    }

    .deleting {
      animation: fadeOut 0.3s forwards;
    }

    @keyframes fadeOut {
      to {
        opacity: 0;
        transform: scale(0.9);
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="premium-badge">
      <i class="fas fa-crown"></i>
      <span>PREMIUM</span>
    </div>
    <h1>QR VIRAL PRO</h1>
    <p>Generador de QR premium con colores vibrantes y diseño profesional</p>
  </header>

  <div class="main">
    <div class="panel-configuracion">
      <div class="form-section">
        <div class="section-title">
          <i class="fas fa-pencil-alt"></i>
          <span>Contenido del QR</span>
        </div>
        <label for="inputLink">Escribí tu dominio o enlace:</label>
        <input type="text" id="inputLink" placeholder="https://miempresa.com/evento" />
        
        <button class="generate-btn" onclick="generarQR()">
          <i class="fas fa-qrcode"></i> Generar y Registrar
        </button>
      </div>

      <div class="style-section">
        <div class="section-title">
          <i class="fas fa-palette"></i>
          <span>Personalización de Colores</span>
        </div>
        
        <div class="color-section">
          <div class="color-header">
            <div class="color-title">
              <i class="fas fa-fill-drip"></i>
              <span>Colores Personalizados</span>
            </div>
            <button class="reset-colors" onclick="resetColors()">
              <i class="fas fa-undo"></i> Reiniciar
            </button>
          </div>
          
          <div class="color-picker-container">
            <div class="color-picker">
              <span class="color-label">Color del QR</span>
              <input type="color" id="qrColor" value="#000000">
              <div class="color-hex" id="qrColorHex">#000000</div>
            </div>
            <div class="color-picker">
              <span class="color-label">Color de Fondo</span>
              <input type="color" id="qrBgColor" value="#ffffff">
              <div class="color-hex" id="qrBgColorHex">#ffffff</div>
            </div>
          </div>
        </div>
        
        <div class="preset-colors">
          <div class="preset-title">
            <i class="fas fa-star"></i>
            <span>ideas</span>
          </div>
          <div class="color-presets">
            <div class="color-preset" style="background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);" data-foreground="#6a11cb" data-background="#2575fc"></div>
            <div class="color-preset" style="background: linear-gradient(135deg, #ff6b6b 0%, #ffa500 100%);" data-foreground="#ff6b6b" data-background="#ffa500"></div>
            <div class="color-preset" style="background: linear-gradient(135deg, #00b09b 0%, #96c93d 100%);" data-foreground="#00b09b" data-background="#96c93d"></div>
            <div class="color-preset" style="background: linear-gradient(135deg, #ff0080 0%, #ff8c00 100%);" data-foreground="#ff0080" data-background="#ff8c00"></div>
          </div>
        </div>
      </div>
    </div>

    <div class="qr-section">
      <div class="section-header">
        <h2><i class="fas fa-folder"></i> QR Registrados</h2>
        <button class="clear-button" onclick="limpiarQRs()">
          <i class="fas fa-trash"></i> Limpiar Todo
        </button>
      </div>
      
      <div class="qr-grid" id="qrLista">
        <div class="empty-state" id="emptyState">
          <i class="fas fa-qrcode"></i>
          <p>No hay códigos QR generados todavía</p>
        </div>
      </div>
    </div>

    <div class="pasos">
      <strong><i class="fas fa-info-circle"></i> ¿Cómo funciona?</strong>
      ✅ Ingresá tu dominio o link personalizado.<br>
      ✅ Elegí colores personalizados o usá nuestras combinaciones predefinidas.<br>
      ✅ Tocá "Generar y Registrar" y el QR se crea arriba.<br>
      ✅ Cada QR tiene su botón de descarga y eliminación individual.<br>
      ✅ Se guardan automáticamente sin borrar ninguno.
    </div>

    <div class="footer">© QR VIRAL PRO 2025 | Sistema Premium - Todos los derechos reservados</div>
  </div>

  <div class="toast" id="toast"></div>

  <script src="https://cdn.jsdelivr.net/npm/qrcode/build/qrcode.min.js"></script>
  <script>
    const qrLista = document.getElementById('qrLista');
    const emptyState = document.getElementById('emptyState');
    const toast = document.getElementById('toast');
    const qrColorInput = document.getElementById('qrColor');
    const qrBgColorInput = document.getElementById('qrBgColor');
    const qrColorHex = document.getElementById('qrColorHex');
    const qrBgColorHex = document.getElementById('qrBgColorHex');
    
    // Actualizar valores hexadecimales de los colores
    function updateColorHex() {
      qrColorHex.textContent = qrColorInput.value;
      qrBgColorHex.textContent = qrBgColorInput.value;
    }
    
    qrColorInput.addEventListener('input', updateColorHex);
    qrBgColorInput.addEventListener('input', updateColorHex);
    
    // Inicializar valores hexadecimales
    updateColorHex();
    
    // Configurar presets de colores
    document.querySelectorAll('.color-preset').forEach(preset => {
      preset.addEventListener('click', function() {
        document.querySelectorAll('.color-preset').forEach(p => p.classList.remove('active'));
        this.classList.add('active');
        
        const foreground = this.getAttribute('data-foreground');
        const background = this.getAttribute('data-background');
        
        qrColorInput.value = foreground;
        qrBgColorInput.value = background;
        updateColorHex();
        
        mostrarToast("Combinación de colores aplicada");
      });
    });
    
    // Reiniciar colores
    function resetColors() {
      qrColorInput.value = '#000000';
      qrBgColorInput.value = '#ffffff';
      updateColorHex();
      document.querySelectorAll('.color-preset').forEach(p => p.classList.remove('active'));
      mostrarToast("Colores reiniciados");
    }
    
    // Función para mostrar notificación
    function mostrarToast(mensaje) {
      toast.innerHTML = `<i class="fas fa-check-circle"></i> ${mensaje}`;
      toast.classList.add('show');
      
      setTimeout(() => {
        toast.classList.remove('show');
      }, 3000);
  }
    function limpiarQRs() {
      if (qrLista.children.length > 1 || (qrLista.children.length === 1 && !qrLista.contains(emptyState))) {
        if (confirm("¿Estás seguro de que querés eliminar todos los códigos QR?")) {
          qrLista.innerHTML = '';
          qrLista.appendChild(emptyState);
          mostrarToast("Todos los QR han sido eliminados");
        }
      }
    }

    function eliminarQR(elemento) {
      if (confirm("¿Estás seguro de que querés eliminar este código QR?")) {
        const tarjeta = elemento.closest('.qr-card');
        tarjeta.classList.add('deleting');
        
        setTimeout(() => {
          tarjeta.remove();
          mostrarToast("QR eliminado correctamente");
          
          // Si no quedan más QR, mostrar el empty state
          if (qrLista.children.length === 0) {
            qrLista.appendChild(emptyState);
          }
        }, 300);
      }
                              }
   function generarQR() {
      const enlace = document.getElementById('inputLink').value.trim();
      if (!enlace) {
        mostrarToast("Por favor ingresá un enlace válido.");
        return;
      }
      
      const qrColor = qrColorInput.value;
      const qrBgColor = qrBgColorInput.value;

      QRCode.toDataURL(enlace, { 
        width: 220, 
        margin: 1,
        color: {
          dark: qrColor,
          light: qrBgColor
        }
      }, function (err, url) {
        if (err) return console.error(err);

        // Ocultar empty state si existe
        if (emptyState.parentElement === qrLista) {
          qrLista.removeChild(emptyState);
        }

        const tarjeta = document.createElement('div');
        tarjeta.className = 'qr-card';

        // Botón de eliminar
        const deleteBtn = document.createElement('button');
        deleteBtn.className = 'delete-btn';
        deleteBtn.innerHTML = '<i class="fas fa-times"></i>';
        deleteBtn.onclick = function() {
          eliminarQR(this);
        };
        tarjeta.appendChild(deleteBtn);

        const imgContainer = document.createElement('div');
        imgContainer.className = 'qr-image-container';
        
        const img = document.createElement('img');
        img.src = url;
        img.alt = "Código QR";
        
        imgContainer.appendChild(img);
        tarjeta.appendChild(imgContainer);

        const texto = document.createElement('div');
        texto.className = 'qr-link';
        texto.textContent = enlace.length > 40 ? enlace.substring(0, 40) + '...' : enlace;
        texto.title = enlace;
        tarjeta.appendChild(texto);

        const actions = document.createElement('div');
        actions.className = 'qr-actions';
        
        const btnDownload = document.createElement('button');
        btnDownload.innerHTML = '<i class="fas fa-download"></i> Descargar';
  btnDownload.onclick = function () {
          const a = document.createElement('a');
          a.href = url;
          a.download = `qr_viral_${Date.now()}.png`;
          document.body.appendChild(a);
          a.click();
          document.body.removeChild(a);
        };
        
        const btnCopy = document.createElement('button');
        btnCopy.innerHTML = '<i class="fas fa-copy"></i> Copiar';
        btnCopy.classList.add('secondary');
        btnCopy.onclick = function () {
          navigator.clipboard.writeText(enlace)
            .then(() => mostrarToast("Enlace copiado al portapapeles"))
            .catch(err => console.error('Error al copiar: ', err));
        };
        
        actions.appendChild(btnDownload);
        actions.appendChild(btnCopy);
        tarjeta.appendChild(actions);
        
        qrLista.prepend(tarjeta);
        mostrarToast("¡QR premium generado con éxito!");
        
        // Limpiar campo de entrada
        document.getElementById('inputLink').value = '';
      });
    }
    
    // Permitir generar QR con la tecla Enter
    document.getElementById('inputLink').addEventListener('keypress', function(e) {
      if (e.key === 'Enter') {
        generarQR();
      }
    });
  </script>

</body>
</html>      
