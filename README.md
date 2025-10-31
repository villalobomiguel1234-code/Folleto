<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Folleto Web - Mi Negocio</title>
  <style>
    /* ---------- Estilos generales ---------- */
    body {
      margin: 0;
      font-family: 'Poppins', Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    /* ---------- Contenedor principal ---------- */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 2rem;
      max-width: 1200px;
      margin: auto;
    }

    /* ---------- Tarjetas del folleto ---------- */
    .card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 1.5rem;
      flex: 1 1 300px;
      max-width: 350px;
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    .card h2 {
      color: #2c3e50;
      margin-top: 1rem;
    }

    /* ---------- Enlace estilo botón ---------- */
    .link-boton {
      display: inline-block;
      background: #3498db;
      color: white;
      padding: 0.75rem 1.5rem;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 1.5rem;
      transition: background 0.3s;
    }

    .link-boton:hover {
      background: #2980b9;
    }

    /* ---------- Footer ---------- */
    footer {
      text-align: center;
      background: #2c3e50;
      color: white;
      padding: 1rem;
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    /* ---------- Adaptabilidad (Responsive) ---------- */
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.5rem;
      }

      .card {
        max-width: 100%;
      }
    }

    @media (max-width: 480px) {
      .container {
        padding: 1rem;
      }

      .link-boton {
        width: 100%;
        display: block;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Folleto Digital - Café El Borrego</h1>
    <p>Disfrutá del mejor café artesanal en un ambiente cálido y moderno.</p>
  </header>

  <section class="container">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Café artesanal">
      <h2>Café Artesanal</h2>
      <p>Granos seleccionados con tueste perfecto para ofrecerte una experiencia única en cada taza.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" alt="Ambiente cómodo">
      <h2>Ambiente Cálido</h2>
      <p>Disfrutá de un lugar acogedor ideal para charlar, estudiar o relajarte con buena música.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5" alt="Postres caseros">
      <h2>Postres Caseros</h2>
      <p>Complementá tu café con nuestras tortas y galletas elaboradas artesanalmente.</p>
    </div>
  </section>

  <div style="text-align:center; margin-bottom:2rem;">
    <a href="https://www.instagram.com" class="link-boton" target="_blank">Más información</a>
  </div>

  <footer>
    &copy; 2025 Café El Borrego - Todos los derechos reservados
  </footer>

</body>
</html>
