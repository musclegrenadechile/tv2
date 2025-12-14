<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muscle Grenade | La Barra Protein - Pantalla TV</title>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@400;600;700;900&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            mgBlack: "#0B0F1A",
            mgCard: "#141A2B",
            mgPink: "#FF4F81",
            mgYellow: "#FFD54F",
            mgOrange: "#FF8C00",
            mgMint: "#A5F3CF",
            mgBlue: "#A5D8FF",
            mgLilac: "#D7B8FF",
            cream: "#FFF8E1",
          },
          fontFamily: {
            sans: ["Montserrat", "sans-serif"],
            heading: ["Bebas Neue", "cursive"],
          },
        }
      }
    }
  </script>

  <style>
    body { margin: 0; background:#0B0F1A; color:#fff; font-family: Montserrat, sans-serif; }
    .slides { position:relative; width:100%; height:100vh; overflow:hidden; }
    .slide { position:absolute; inset:0; opacity:0; transition: opacity 1.2s ease; display:flex; align-items:center; justify-content:center; padding:48px; }
    .slide.active { opacity:1; z-index:10; }

    .bg1 { background: radial-gradient(circle at top, #FF4F81, #0B0F1A 60%, #000); }
    .bg2 { background: linear-gradient(135deg, #0B0F1A, #1B2A4A, #0B0F1A); }
    .bg3 { background: linear-gradient(135deg, #0B0F1A, #3B1C6D, #0B0F1A); }
    .bg4 { background: radial-gradient(circle at center, #FF8C00, #0B0F1A 60%, #000); }
    .bg5 { background: linear-gradient(135deg, #0B0F1A, #141A2B, #0B0F1A); }

    .title { font-family: "Bebas Neue", cursive; letter-spacing: .16em; text-transform: uppercase; text-shadow: 0 8px 22px rgba(0,0,0,.55); }
    .card { background: rgba(20,26,43,.78); border: 1px solid rgba(255,255,255,.12); border-radius: 28px; box-shadow: 0 18px 40px rgba(0,0,0,.6); backdrop-filter: blur(12px); }
    .pill { border-radius: 9999px; padding: .45rem 1.1rem; font-weight: 800; letter-spacing:.06em; }
    .strike { text-decoration: line-through; opacity:.75; }
  </style>
</head>

<body>
  <div class="slides">

    <!-- SLIDE 1: Branding + frase -->
    <section class="slide active bg5">
      <div class="max-w-6xl w-full grid grid-cols-1 lg:grid-cols-2 gap-10 items-center">
        <div>
          <div class="flex flex-wrap items-center gap-3 mb-6">
            <span class="pill bg-mgOrange text-mgBlack">MUSCLE GRENADE</span>
            <span class="pill bg-mgMint text-mgBlack">LA BARRA PROTEIN</span>
            <span class="pill bg-mgPink text-white">PANTALLA OFICIAL</span>
          </div>

          <h1 class="title text-6xl lg:text-7xl text-cream mb-4">SÁBADO · OFERTAS Y CAFETERÍA</h1>

          <p class="text-2xl lg:text-3xl font-extrabold text-mgYellow mb-4">
            ⭐ FRASE DEL DÍA: “La disciplina se nota cuando nadie está mirando. Hoy cuenta.” ⭐
          </p>

          <p class="text-xl lg:text-2xl text-white/85">
            Suplementos + barra proteica + frapuchinos con proteína. Todo en un mismo lugar.
          </p>

          <div class="mt-8 grid grid-cols-1 sm:grid-cols-3 gap-4">
            <div class="card p-5">
              <p class="text-sm font-bold text-white/70 mb-1">Hoy</p>
              <p class="text-2xl font-black text-cream">Ofertas del día</p>
            </div>
            <div class="card p-5">
              <p class="text-sm font-bold text-white/70 mb-1">La Barra</p>
              <p class="text-2xl font-black text-cream">Cafetería</p>
            </div>
            <div class="card p-5">
              <p class="text-sm font-bold text-white/70 mb-1">La Barra</p>
              <p class="text-2xl font-black text-cream">Frapuchinos Protein</p>
            </div>
          </div>
        </div>

        <div class="card p-8">
          <p class="title text-5xl text-mgYellow mb-4">Recomendado hoy</p>
          <p class="text-3xl font-black mb-2">Combo FrapuChoco Protein</p>
          <p class="text-xl text-white/85 mb-4">Incluye topping a elección (Arándano / Frutilla / Plátano)</p>
          <div class="flex items-baseline gap-4">
            <span class="text-2xl font-bold text-white/80">Super oferta</span>
            <span class="text-6xl font-black text-mgYellow">$5.990.-</span>
          </div>
          <p class="mt-5 text-lg text-white/75">Pídelo directo en el mesón 💬</p>
        </div>
      </div>
    </section>

    <!-- SLIDE 2: Ofertas suplementos -->
    <section class="slide bg1">
      <div class="max-w-6xl w-full">
        <h2 class="title text-6xl lg:text-7xl text-cream text-center mb-10">OFERTAS DEL DÍA</h2>

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">

          <div class="card p-7">
            <div class="flex items-center justify-between mb-3">
              <span class="pill bg-mgBlue text-mgBlack">OMEGA CLÍNICA</span>
              <span class="text-white/75 font-semibold">NAD+ 100 servicios</span>
            </div>
            <p class="text-2xl font-black mb-2">NAD+ Omega Clínica</p>
            <p class="text-lg strike mb-1">Antes $34.990.-</p>
            <p class="text-4xl font-black text-mgYellow">Ahora $25.000.-</p>
            <p class="mt-3 text-white/80">Energía celular · recuperación · bienestar</p>
          </div>

          <div class="card p-7">
            <div class="flex items-center justify-between mb-3">
              <span class="pill bg-mgMint text-mgBlack">PACK FUERZA</span>
              <span class="text-white/75 font-semibold">Army Labs</span>
            </div>
            <p class="text-2xl font-black mb-2">Proteína 5 lb + Creatina</p>
            <p class="text-lg strike mb-1">Antes $79.990.-</p>
            <p class="text-4xl font-black text-mgYellow">Ahora $54.990.-</p>
            <p class="mt-3 text-white/80">Volumen · fuerza · rendimiento</p>
          </div>

          <div class="card p-7">
            <div class="flex items-center justify-between mb-3">
              <span class="pill bg-mgPink text-white">PRE-ENTRENO</span>
              <span class="text-white/75 font-semibold">Killer Pump</span>
            </div>
            <p class="text-2xl font-black mb-2">Killer Pump</p>
            <p class="text-lg strike mb-1">Antes $29.990.-</p>
            <p class="text-4xl font-black text-mgYellow">Ahora $21.990.-</p>
            <p class="mt-3 text-white/80">Enfoque · energía · congestión</p>
          </div>

        </div>

        <p class="text-center text-2xl lg:text-3xl mt-10 text-white/90">
          Pide las ofertas en el mesón 💬
        </p>
      </div>
    </section>

    <!-- SLIDE 3: Cafetería (sin proteína) -->
    <section class="slide bg2">
      <div class="max-w-5xl w-full">
        <h2 class="title text-6xl lg:text-7xl text-cream text-center mb-10">CAFETERÍA</h2>

        <div class="card p-8">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-2xl lg:text-3xl">
            <div class="flex justify-between"><span class="font-semibold">Espresso</span><span class="font-black">$2.000</span></div>
            <div class="flex justify-between"><span class="font-semibold">Americano</span><span class="font-black">$2.500</span></div>
            <div class="flex justify-between"><span class="font-semibold">Latte</span><span class="font-black">$2.800</span></div>
            <div class="flex justify-between"><span class="font-semibold">Capuchino</span><span class="font-black">$2.900</span></div>
            <div class="flex justify-between"><span class="font-semibold">Mocha</span><span class="font-black">$3.200</span></div>
            <div class="flex justify-between"><span class="font-semibold">Café doble</span><span class="font-black">$3.000</span></div>
            <div class="flex justify-between"><span class="font-semibold">Leche vegetal</span><span class="font-black">+$300</span></div>
            <div class="flex justify-between"><span class="font-semibold">Extra shot</span><span class="font-black">+$500</span></div>
          </div>
        </div>

        <p class="text-center text-2xl lg:text-3xl mt-10 text-white/85">
          Café tradicional, rápido y rico ☕
        </p>
      </div>
    </section>

    <!-- SLIDE 4: Frapuchinos con proteína -->
    <section class="slide bg3">
      <div class="max-w-6xl w-full">
        <h2 class="title text-6xl lg:text-7xl text-cream text-center mb-10">FRAPUCHINOS CON PROTEÍNA</h2>

        <div class="card p-8">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-5 text-2xl lg:text-3xl">
            <div class="flex justify-between"><span class="font-semibold">FrapuChoco Protein (Volcán de Chocolate)</span><span class="font-black">$3.490</span></div>
            <div class="flex justify-between"><span class="font-semibold">FrapuVainilla Protein</span><span class="font-black">$3.490</span></div>
            <div class="flex justify-between"><span class="font-semibold">FrapuFrutilla Protein</span><span class="font-black">$3.990</span></div>
            <div class="flex justify-between"><span class="font-semibold">FrapuPlátano Protein</span><span class="font-black">$3.990</span></div>
            <div class="flex justify-between"><span class="font-semibold">Smoothie Energía (Frutilla/Plátano + Protein)</span><span class="font-black">$3.990</span></div>
            <div class="flex justify-between"><span class="font-semibold">Smoothie Detox Verde (+ Protein)</span><span class="font-black">$3.990</span></div>
            <div class="flex justify-between"><span class="font-semibold">Shot extra de proteína</span><span class="font-black">$1.000</span></div>
            <div class="flex justify-between"><span class="font-semibold">Topping (Arándano / Frutilla / Plátano)</span><span class="font-black">+$1.000</span></div>
          </div>
        </div>

        <p class="text-center text-2xl lg:text-3xl mt-10 text-white/85">
          Pide tu frapu en el mesón 🥤💪
        </p>
      </div>
    </section>

    <!-- SLIDE 5: Combo del día -->
    <section class="slide bg4">
      <div class="max-w-6xl w-full text-center">
        <p class="title text-4xl lg:text-5xl text-mgYellow tracking-[0.35em] mb-3">COMBO DEL DÍA</p>
        <h2 class="title text-7xl lg:text-[8rem] text-cream mb-8">FRAPUCHOCO PROTEIN</h2>

        <div class="card p-10 max-w-5xl mx-auto">
          <p class="text-3xl lg:text-4xl font-black mb-3">Super oferta</p>
          <p class="text-2xl lg:text-3xl text-white/90 mb-6">
            Incluye topping a elección: <span class="text-mgYellow font-black">Arándano · Frutilla · Plátano</span>
          </p>
          <p class="text-6xl lg:text-7xl font-black text-mgYellow">$5.990.-</p>
          <p class="mt-5 text-xl lg:text-2xl text-white/80">
            Pídelo como: <span class="font-black text-cream">“Combo FrapuChoco Protein”</span>
          </p>
        </div>

        <p class="mt-10 text-2xl lg:text-3xl text-white/90">
          Muscle Grenade · La Barra Protein
        </p>
      </div>
    </section>

  </div>

  <script>
    const slides = document.querySelectorAll(".slide");
    let i = 0;
    const intervalMs = 9000;

    function show(idx){
      slides.forEach(s => s.classList.remove("active"));
      slides[idx].classList.add("active");
    }

    show(i);
    setInterval(() => {
      i = (i + 1) % slides.length;
      show(i);
    }, intervalMs);
  </script>
</body>
</html>
