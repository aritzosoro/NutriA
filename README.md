# NutriA
La mejor web para buscar las mejores INTELIGENCIAS ARTIFICIALES en el 2025 - PROXIMA actualicación mejorada en 2026...
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Más que una web de nutrición: somos tu espacio de transformación, donde la ciencia, la motivación y la salud se unen para que alcances tu mejor versión.">
  <title>NutrIA | IA para Bienestar</title>
  <style>
    :root {
      --primary: #5D3A9B;
      --primary-light: #7A5BBF;
      --text: #1a1a2e;
      --text-light: #5a5a72;
      --bg: #ffffff;
      --bg-light: #fafbff;
      --border: #eaeef5;
      --radius: 18px;
      --shadow: 0 6px 20px rgba(93, 58, 155, 0.06);
      --transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background-color: var(--bg-light);
      color: var(--text);
      line-height: 1.65;
      padding: 3rem 1.5rem;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
    }

    header {
      text-align: center;
      margin-bottom: 3.5rem;
    }

    h1 {
      font-size: 2.4rem;
      font-weight: 800;
      color: var(--primary);
      margin-bottom: 1.2rem;
    }

    .tagline {
      font-size: 1.2rem;
      color: var(--text-light);
      line-height: 1.6;
      max-width: 700px;
      margin: 0 auto;
    }

    .intro {
      background: var(--bg);
      padding: 1.8rem;
      border-radius: var(--radius);
      margin-bottom: 3rem;
      border-left: 3px solid var(--primary);
      font-size: 1.02rem;
      color: var(--text-light);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 2rem;
    }

    .card {
      background: var(--bg);
      border-radius: var(--radius);
      padding: 2rem;
      box-shadow: var(--shadow);
      position: relative;
      overflow: hidden;
      transition: var(--transition);
      border: 1px solid var(--border);
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 28px rgba(93, 58, 155, 0.12);
    }

    /* Núcleo animado dentro de cada tarjeta */
    .nucleo {
      position: absolute;
      top: 24px;
      right: 24px;
      width: 36px;
      height: 36px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .nucleo-circle {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      background: conic-gradient(from 0deg, var(--primary), var(--primary-light), var(--primary));
      animation: rotateNucleo 12s linear infinite;
      box-shadow: 0 2px 6px rgba(93, 58, 155, 0.2);
    }

    @keyframes rotateNucleo {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    .card h2 {
      font-size: 1.35rem;
      margin-bottom: 1rem;
      color: var(--primary);
      font-weight: 700;
    }

    .card p {
      color: var(--text-light);
      margin-bottom: 1.2rem;
      font-size: 0.98rem;
      line-height: 1.7;
    }

    .card a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 600;
      font-size: 0.98rem;
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
    }

    .card a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      margin-top: 4rem;
      padding-top: 2rem;
      color: var(--text-light);
      font-size: 0.95rem;
      border-top: 1px solid var(--border);
    }

    @media (max-width: 650px) {
      body {
        padding: 2rem 1.2rem;
      }
      h1 {
        font-size: 2rem;
      }
      .tagline {
        font-size: 1.05rem;
      }
      .grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>NutrIA</h1>
      <p class="tagline">
        Más que una web de nutrición: somos tu espacio de transformación, donde la ciencia, la motivación y la salud se unen para que alcances tu mejor versión. Vive con pasión y cuida tu nutrición.
      </p>
    </header>

    <div class="intro">
      <p>
        Las siguientes plataformas utilizan inteligencia artificial avanzada para ofrecerte planes alimenticios personalizados, seguimiento de hábitos y orientación basada en evidencia. 
        <strong>No reemplazan la atención médica profesional</strong>, pero son aliadas poderosas en tu viaje hacia una vida más saludable.
      </p>
    </div>

    <div class="grid">
      <div class="card">
        <div class="nucleo">
          <div class="nucleo-circle"></div>
        </div>
        <h2>Qwen (Tongyi Qianwen)</h2>
        <p>IA multimodal de Alibaba capaz de generar planes de alimentación personalizados, calcular requerimientos calóricos y ofrecer seguimiento conductual. Soporta múltiples idiomas.</p>
        <a href="https://qwen.ai" target="_blank" rel="noopener noreferrer">Explorar Qwen →</a>
      </div>

      <div class="card">
        <div class="nucleo">
          <div class="nucleo-circle"></div>
        </div>
        <h2>ChatGPT (OpenAI)</h2>
        <p>Con GPT-4, obtén menús semanales, ajuste de recetas, análisis nutricional y apoyo motivacional. Ideal para flexibilidad y profundidad en tus recomendaciones dietéticas.</p>
        <a href="https://chat.openai.com" target="_blank" rel="noopener noreferrer">Ir a ChatGPT →</a>
      </div>

      <div class="card">
        <div class="nucleo">
          <div class="nucleo-circle"></div>
        </div>
        <h2>Claude (Anthropic)</h2>
        <p>Diseñada con principios éticos, evita dietas extremas y promueve una relación equilibrada con la comida. Excelente para bienestar mental y físico a largo plazo.</p>
        <a href="https://claude.ai" target="_blank" rel="noopener noreferrer">Probar Claude →</a>
      </div>

      <div class="card">
        <div class="nucleo">
          <div class="nucleo-circle"></div>
        </div>
        <h2>Google Gemini</h2>
        <p>Integrado con herramientas de Google, te permite planificar comidas, analizar etiquetas nutricionales y generar recetas saludables con los ingredientes que tienes a mano.</p>
        <a href="https://gemini.google.com" target="_blank" rel="noopener noreferrer">Usar Gemini →</a>
      </div>

      <div class="card">
        <div class="nucleo">
          <div class="nucleo-circle"></div>
        </div>
        <h2>Apps Especializadas</h2>
        <p>Plataformas como <strong>Lose It!</strong> o <strong>MyFitnessPal</strong> combinan IA con bases de datos nutricionales para seguimiento preciso de calorías y macronutrientes.</p>
        <a href="https://www.loseit.com" target="_blank" rel="noopener noreferrer">Visitar Lose It! →</a>
      </div>
    </div>

    <footer>
      <p><strong>Nota:</strong> La inteligencia artificial es una herramienta complementaria. Consulta siempre con un nutricionista o profesional de la salud antes de realizar cambios significativos en tu dieta.</p>
      <p>© 2025 NutrIA — Ciencia, tecnología y bienestar en equilibrio</p>
    </footer>
  </div>

</body>
</html>

