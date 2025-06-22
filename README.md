<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reconnect & Wake: A Balanced Guide to Ancient Rhythms and Modern Well-Being</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Lora:ital,wght@0,400;0,700;1,400;1,700&family=Pacifico&display=swap" rel="stylesheet">
  <style>
    html { scroll-behavior: smooth; }
    :root {
      --color-sandstone: #E3C0A0;
      --color-terracotta: #A52A2A;
      --color-indigo: #4B0082;
      --color-gold-foil: #D4AF37;
      --color-charcoal-black: #333333;
      --color-soft-white: #F8F8F8;
    }
    .bg-sandstone { background-color: var(--color-sandstone); }
    .text-sandstone { color: var(--color-sandstone); }
    .bg-terracotta { background-color: var(--color-terracotta); }
    .text-terracotta { color: var(--color-terracotta); }
    .bg-indigo { background-color: var(--color-indigo); }
    .text-indigo { color: var(--color-indigo); }
    .bg-gold-foil { background-color: var(--color-gold-foil); }
    .text-gold-foil { color: var(--color-gold-foil); }
    .bg-charcoal-black { background-color: var(--color-charcoal-black); }
    .text-charcoal-black { color: var(--color-charcoal-black); }
    .text-soft-white { color: var(--color-soft-white); }

    .font-main-title { font-family: 'Bebas Neue', sans-serif; letter-spacing: 0.05em; }
    .font-subtitle-font { font-family: 'Lora', serif; }
    .font-body-text { font-family: 'Lora', serif; }
    .font-section-header { font-family: 'Pacifico', cursive; }

    .ebook-page {
      width: 100%;
      max-width: 800px;
      margin: 2rem auto;
      border: 1px solid rgba(0,0,0,0.05);
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      position: relative;
      border-radius: 0.5rem;
      display: flex;
      flex-direction: column;
      padding: 2rem;
      background-clip: padding-box;
      transition: box-shadow 0.2s;
    }
    .ebook-page:hover {
      box-shadow: 0 8px 32px rgba(75,0,130,0.10), 0 2px 8px rgba(165,42,42,0.05);
    }
    @media (min-width: 768px) {
      .ebook-page { padding: 3rem; }
    }
    .distressed-bg-light {
      background-color: var(--color-sandstone);
      background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="10" cy="10" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="50" cy="50" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="90" cy="90" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="10" cy="90" r="2" fill="%234B0082" opacity="0.05"/><circle cx="90" cy="10" r="2" fill="%234B0082" opacity="0.05"/></svg>');
      background-size: 50px 50px;
      background-repeat: repeat;
    }
    .distressed-bg-dark {
      background-color: var(--color-charcoal-black);
      background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="10" cy="10" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="50" cy="50" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="90" cy="90" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="10" cy="90" r="2" fill="%23D4AF37" opacity="0.05"/><circle cx="90" cy="10" r="2" fill="%23D4AF37" opacity="0.05"/></svg>');
      background-size: 50px 50px;
      background-repeat: repeat;
    }
    .info-box {
      padding: 0.75rem 1rem;
      border-radius: 0.5rem;
      margin-top: 1rem;
      font-size: 0.95rem;
      line-height: 1.5;
      border-left-width: 4px;
      box-shadow: 0 1px 6px rgba(0,0,0,0.06);
      transition: background 0.2s;
    }
    .info-box.science {
      background-color: rgba(165, 42, 42, 0.1);
      border-color: var(--color-terracotta);
      color: var(--color-charcoal-black);
    }
    .info-box.contrary {
      background-color: rgba(75, 0, 130, 0.1);
      border-color: var(--color-indigo);
      color: var(--color-charcoal-black);
    }
    .info-box.advice {
      background-color: rgba(212, 175, 55, 0.1);
      border-color: var(--color-gold-foil);
      color: var(--color-charcoal-black);
    }
    .info-box h3 {
      font-weight: 700;
      margin-bottom: 0.25rem;
    }
    .info-box ul {
      list-style: disc;
      padding-left: 1.25rem;
    }
    .info-box ul li {
      margin-bottom: 0.1rem;
    }
    .pull-quote {
      font-family: 'Pacifico', cursive;
      font-size: 1.75rem;
      line-height: 1.3;
      padding: 1rem;
      margin: 1.5rem 0;
      text-align: center;
      color: var(--color-gold-foil);
      background-color: rgba(255, 255, 255, 0.08);
      border-radius: 0.5rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      letter-spacing: 0.03em;
    }
    .tribal-divider {
      border: none;
      border-top: 2px dashed rgba(0,0,0,0.3);
      margin: 2rem 0;
      width: 80%;
      opacity: 0.7;
    }
    .water-margin-quote {
      font-family: 'Lora', serif;
      font-style: italic;
      font-size: 1.1rem;
      text-align: right;
      margin-top: 2rem;
      padding: 0.5rem 1rem;
      background-color: rgba(75, 0, 130, 0.05);
      color: var(--color-indigo);
      border-radius: 0.25rem;
    }
    .chapter-icon {
      flex-shrink: 0;
      width: 40px;
      height: 40px;
    }
    .toc-link {
      display: block;
      padding: 0.5rem 1rem;
      border-radius: 0.375rem;
      font-weight: 500;
      transition: background 0.18s, color 0.18s, box-shadow 0.18s;
      color: var(--color-indigo);
      background: rgba(212,175,55,0.04);
      box-shadow: 0 1px 3px rgba(75,0,130,0.03);
      text-decoration: none;
    }
    .toc-link:hover, .toc-link:focus {
      background: linear-gradient(90deg, #E3C0A0 0%, #D4AF37 100%);
      color: #A52A2A;
      box-shadow: 0 2px 8px rgba(212,175,55,0.10);
      outline: none;
      text-decoration: underline;
    }
    #backToTop {
      position: fixed;
      bottom: 32px;
      right: 32px;
      background: linear-gradient(90deg, #D4AF37 60%, #A52A2A 100%);
      color: #fff;
      padding: 0.75rem 1.25rem;
      border-radius: 9999px;
      font-family: 'Bebas Neue', sans-serif;
      font-size: 1.25rem;
      box-shadow: 0 4px 16px rgba(75,0,130,0.16);
      border: none;
      cursor: pointer;
      opacity: 0;
      pointer-events: none;
      z-index: 50;
      transition: opacity 0.25s;
      letter-spacing: 0.07em;
    }
    #backToTop.show {
      opacity: 1;
      pointer-events: auto;
    }
  </style>
</head>
<body class="bg-gray-100 font-body-text text-charcoal-black">

  <!-- Cover Page -->
  <section class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center" id="cover">
    <div class="relative z-10 flex flex-col items-center">
      <h1 class="text-7xl md:text-9xl font-main-title leading-none mb-4 text-gold-foil drop-shadow-lg tracking-wider">RAW</h1>
      <h2 class="text-4xl md:text-5xl font-subtitle-font leading-tight mb-6 text-soft-white tracking-wide">Reconnect And Wake</h2>
      <div class="my-6 w-[200px] h-[150px]">
        <!-- Cover SVG omitted for brevity, include your SVG here if needed -->
      </div>
      <p class="text-xl md:text-2xl font-body-text mt-6 text-soft-white opacity-90">
        A science-informed guide to raw nourishment, circadian rhythm, contrast therapy, emotional well-being, and connection, blending ancestral wisdom with modern evidence.
      </p>
      <p class="text-lg font-subtitle-font italic mt-4 text-soft-white">Speak Love to Your Life</p>
    </div>
  </section>

  <!-- Back Cover / Overall Blurb -->
  <section class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white" id="blurb">
    <div class="relative z-10 p-6">
      <h3 class="text-3xl font-subtitle-font mb-8">
        "A science-informed guide to ancestral rhythms and modern well-being."
      </h3>
      <div class="my-8 w-[250px] h-[180px] mx-auto opacity-70">
        <!-- Blurb SVG omitted for brevity, include your SVG here if needed -->
      </div>
      <p class="text-xl font-body-text mt-4 opacity-80">
        Dive deep into ancestral wisdom, backed by modern science, to reconnect with your natural rhythms and embrace a balanced, thriving life.
      </p>
    </div>
  </section>

  <!-- Table of Contents -->
  <nav class="ebook-page distressed-bg-light" aria-label="Table of Contents" id="toc">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">📖</span> Table of Contents
    </h2>
    <ol class="list-decimal list-inside text-lg font-body-text space-y-2">
      <li><a href="#introduction" class="toc-link">Introduction</a></li>
      <li><a href="#raw-meat" class="toc-link">Raw Meat – Nourishment with Caution</a></li>
      <li><a href="#morning-sunlight" class="toc-link">Morning Sunlight</a></li>
      <li><a href="#circadian-rhythm" class="toc-link">Circadian Rhythm</a></li>
      <li><a href="#contrast-therapy" class="toc-link">Contrast Therapy</a></li>
      <li><a href="#relationships" class="toc-link">Relationships</a></li>
      <li><a href="#self-compassion" class="toc-link">Self-Compassion</a></li>
      <li><a href="#habits" class="toc-link">Habits</a></li>
      <li><a href="#water-intention" class="toc-link">Water and Intention</a></li>
      <li><a href="#baking-soda" class="toc-link">Baking Soda</a></li>
      <li><a href="#wholeness" class="toc-link">Wholeness</a></li>
      <li><a href="#you-can" class="toc-link">You CAN – Closing Spread</a></li>
      <li><a href="#summary-table" class="toc-link">Summary Table</a></li>
    </ol>
  </nav>

  <!-- Introduction -->
  <section class="ebook-page distressed-bg-light" id="introduction">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 chapter-icon">
        <!-- Section SVG omitted for brevity -->
      </span>
      Introduction
    </h2>
    <p class="mb-6 font-body-text text-lg">
      Modern life, with artificial lights and processed foods, can disconnect us from natural rhythms. Our ancestors rose with the sun, ate whole foods, and lived in close communities. This guide integrates these practices with science to enhance well-being, acknowledging both evidence and limitations.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <p>A 2021 Nature Reviews Endocrinology review shows modern lifestyles disrupt circadian and metabolic health (<a href="https://doi.org/10.1038/s41574-021-00490-3" target="_blank" class="text-indigo underline">DOI: 10.1038/s41574-021-00490-3</a>).</p>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <p>Ancestral practices may not suit everyone due to individual needs or modern constraints.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Raw Meat – Nourishment with Caution -->
  <section class="ebook-page distressed-bg-light" id="raw-meat">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">🥩</span>
      Raw Meat – Nourishment with Caution
    </h2>
    <p class="mb-4 font-body-text">
      Raw meat, when responsibly sourced, retains nutrients like enzymes and B vitamins that cooking may reduce. Cultures like the Inuit and Japanese consume raw liver or sashimi, suggesting benefits. Pair with lime juice or vinegar for digestion and microbial safety.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Cooking reduces B vitamins by up to 40% (Food Chemistry, 2019, <a href="https://doi.org/10.1016/j.foodchem.2018.07.174" target="_blank" class="text-indigo underline">DOI: 10.1016/j.foodchem.2018.07.174</a>).</li>
        <li>Inuit diets show low heart disease rates (Nutrition Research Reviews, 2014, <a href="https://doi.org/10.1017/S0954422414000116" target="_blank" class="text-indigo underline">DOI: 10.1017/S0954422414000116</a>).</li>
        <li>Whole-food diets improve mood (Frontiers in Psychology, 2020, <a href="https://doi.org/10.3389/fpsyg.2020.00557" target="_blank" class="text-indigo underline">DOI: 10.3389/fpsyg.2020.00557</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Raw meat risks pathogens like Salmonella (PMC, 2023, <a href="https://doi.org/10.1093/fqsafe/fyad010" target="_blank" class="text-indigo underline">DOI: 10.1093/fqsafe/fyad010</a>).</li>
        <li>Claims of clearer skin or reduced inflammation lack evidence; plant-based diets may reduce inflammation more (The Healthy, 2022).</li>
        <li>Raw diets may lack fiber, risking imbalances.</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Use grass-fed, pasture-raised meat, freeze briefly, and consult a nutritionist. Raw meat isn’t for everyone.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Morning Sunlight -->
  <section class="ebook-page distressed-bg-light" id="morning-sunlight">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">☀️</span>
      Morning Sunlight
    </h2>
    <p class="mb-4 font-body-text">
      Morning sunlight resets your circadian rhythm, boosting alertness and improving sleep, mood, and energy. Aim for 10–30 minutes without sunglasses or windows.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Light synchronizes the suprachiasmatic nucleus (PMC, 2019, <a href="https://doi.org/10.1098/rsfs.2019.0098" target="_blank" class="text-indigo underline">DOI: 10.1098/rsfs.2019.0098</a>).</li>
        <li>Morning light enhances alertness (Elife, 2020, <a href="https://doi.org/10.7554/eLife.61682" target="_blank" class="text-indigo underline">DOI: 10.7554/eLife.61682</a>).</li>
        <li>Light exposure reduces depression (Journal of Affective Disorders, 2019, <a href="https://doi.org/10.1016/j.jad.2018.10.098" target="_blank" class="text-indigo underline">DOI: 10.1016/j.jad.2018.10.098</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Sunlight access is limited by climate or schedules.</li>
        <li>Eye conditions may require caution (Ophthalmology, 2021, <a href="https://doi.org/10.1016/j.ophtha.2020.07.014" target="_blank" class="text-indigo underline">DOI: 10.1016/j.ophtha.2020.07.014</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Get sunlight exposure or use a 10,000-lux light therapy lamp. Consult a doctor if light-sensitive.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Circadian Rhythm -->
  <section class="ebook-page distressed-bg-light" id="circadian-rhythm">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">⏰</span>
      Circadian Rhythm
    </h2>
    <p class="mb-4 font-body-text">
      Your body’s clock, influenced by light, food, and movement, governs health. Align by rising with the sun, dimming lights at night, and eating consistently.
    </p>
    <div class="my-6">
      <h3 class="text-2xl font-subtitle-font text-terracotta mb-4 text-center">Circadian Rhythm Infographic</h3>
      <div class="bg-charcoal-black text-soft-white p-6 rounded-lg shadow-md">
        <p class="text-xl font-main-title mb-2 text-gold-foil">Daily Rhythm Planner:</p>
        <ul class="list-none space-y-2 text-lg">
          <li><strong class="text-gold-foil">WAKE:</strong> Light at dawn &rarr; Cortisol peak.</li>
          <li><strong class="text-gold-foil">MOVE:</strong> Energy high.</li>
          <li><strong class="text-gold-foil">EAT:</strong> Consistent meal timing.</li>
          <li><strong class="text-gold-foil">REST:</strong> Digest & recover.</li>
          <li><strong class="text-gold-foil">DARKNESS:</strong> Dim lights &rarr; Melatonin release.</li>
          <li><strong class="text-gold-foil">SLEEP:</strong> Restore completely.</li>
        </ul>
        <p class="text-sm mt-4 text-soft-white/80 text-right">
          *Infographic Concept: Sun/moon cycle with time markers for key phases.*
        </p>
      </div>
    </div>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Circadian alignment improves metabolism (Nature Reviews Endocrinology, 2021, <a href="https://doi.org/10.1038/s41574-021-00490-3" target="_blank" class="text-indigo underline">DOI: 10.1038/s41574-021-00490-3</a>).</li>
        <li>Meal timing synchronizes clocks (Sleep Medicine Reviews, 2016, <a href="https://doi.org/10.1016/j.smrv.2016.08.001" target="_blank" class="text-indigo underline">DOI: 10.1016/j.smrv.2016.08.001</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Shift work or genetics (e.g., night owls) complicates alignment (Nature Communications, 2019, <a href="https://doi.org/10.1038/s41467-019-08976-3" target="_blank" class="text-indigo underline">DOI: 10.1038/s41467-019-08976-3</a>).</li>
        <li>Artificial light is less effective (Journal of Biological Rhythms, 2020, <a href="https://doi.org/10.1177/0748730420908053" target="_blank" class="text-indigo underline">DOI: 10.1177/0748730420908053</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Follow natural light cycles when possible or use light therapy. Tailor schedules with a sleep specialist.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Contrast Therapy -->
  <section class="ebook-page distressed-bg-light" id="contrast-therapy">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">🔥💧</span>
      Contrast Therapy
    </h2>
    <p class="mb-4 font-body-text">
      Alternating hot (sauna) and cold (plunge) exposure may improve blood flow, reduce inflammation, and build resilience.
    </p>
    <div class="my-6">
      <h3 class="text-2xl font-subtitle-font text-terracotta mb-4 text-center">Contrast Therapy Infographic</h3>
      <div class="bg-charcoal-black text-soft-white p-6 rounded-lg shadow-md">
        <div class="flex justify-between items-center mb-4">
          <span class="text-6xl text-terracotta">🔥</span>
          <div class="flex-1 mx-4">
            <div class="h-4 bg-gradient-to-r from-red-800 to-blue-800 rounded-full"></div>
          </div>
          <span class="text-6xl text-indigo">❄️</span>
        </div>
        <p class="text-xl font-main-title mb-2 text-gold-foil text-center">Hot/Cold Cycle Tips:</p>
        <ul class="list-disc list-inside text-lg text-center mx-auto max-w-sm">
          <li><strong class="text-gold-foil">Hot:</strong> 2–3 minutes (Sauna/Hot Shower)</li>
          <li><strong class="text-gold-foil">Cold:</strong> 30–60 seconds (Cold Plunge/Shower)</li>
          <li><strong class="text-gold-foil">Cycles:</strong> Repeat 3–5 times</li>
          <li><strong class="text-gold-foil">Start Gentle:</strong> Listen to your body.</li>
          <li><strong class="text-gold-foil">Breathe Deep:</strong> Focus on calm.</li>
        </ul>
        <p class="text-sm mt-4 text-soft-white/80 text-right">
          *Infographic Concept: Hot/cold gradient with duration tips.*
        </p>
      </div>
    </div>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Contrast baths aid muscle recovery (Journal of Athletic Training, 2018, <a href="https://doi.org/10.4085/1062-6050-127-17" target="_blank" class="text-indigo underline">DOI: 10.4085/1062-6050-127-17</a>).</li>
        <li>Cold exposure reduces anxiety (International Journal of Environmental Research and Public Health, 2021, <a href="https://doi.org/10.3390/ijerph18073572" target="_blank" class="text-indigo underline">DOI: 10.3390/ijerph18073572</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Nervous system “reset” claims lack direct evidence (Scientific Reports, 2020, <a href="https://doi.org/10.1038/s41598-020-61134-7" target="_blank" class="text-indigo underline">DOI: 10.1038/s41598-020-61134-7</a>).</li>
        <li>Risks exist for heart conditions (Mayo Clinic Proceedings, 2018, <a href="https://doi.org/10.1016/j.mayocp.2018.04.008" target="_blank" class="text-indigo underline">DOI: 10.1016/j.mayocp.2018.04.008</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Try 2–3 minutes hot, 30–60 seconds cold, 3–5 cycles. Start slowly and consult a doctor if at risk.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Relationships -->
  <section class="ebook-page distressed-bg-light" id="relationships">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">🫂</span>
      Relationships
    </h2>
    <p class="mb-4 font-body-text">
      Strong connections with friends, family, or partners release oxytocin, reducing stress and promoting healing.
    </p>
    <p class="pull-quote">“We heal in safe company.”</p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Social bonds reduce mortality by 50% (PLoS Medicine, 2010, <a href="https://doi.org/10.1371/journal.pmed.1000316" target="_blank" class="text-indigo underline">DOI: 10.1371/journal.pmed.1000316</a>).</li>
        <li>Oxytocin boosts immunity (Neuroscience & Biobehavioral Reviews, 2016, <a href="https://doi.org/10.1016/j.neubiorev.2015.12.004" target="_blank" class="text-indigo underline">DOI: 10.1016/j.neubiorev.2015.12.004</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Introverts may thrive with less interaction (Personality and Social Psychology Bulletin, 2019, <a href="https://doi.org/10.1177/0146167218793742" target="_blank" class="text-indigo underline">DOI: 10.1177/0146167218793742</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Nurture relationships through shared meals or touch. Respect your social needs.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Self-Compassion -->
  <section class="ebook-page distressed-bg-light" id="self-compassion">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">🧘‍♀️</span>
      Self-Compassion
    </h2>
    <p class="mb-4 font-body-text">
      Kind thoughts and emotional expression support mental and physical health.
    </p>
    <p class="pull-quote">“Be kind to the one you live inside.”</p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Self-compassion lowers anxiety (Mindfulness, 2019, <a href="https://doi.org/10.1007/s12671-019-01134-2" target="_blank" class="text-indigo underline">DOI: 10.1007/s12671-019-01134-2</a>).</li>
        <li>Emotional expression reduces inflammation (Emotion, 2017, <a href="https://doi.org/10.1037/emo0000282" target="_blank" class="text-indigo underline">DOI: 10.1037/emo0000282</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Over-expression may amplify negativity (Journal of Social and Clinical Psychology, 2016, <a href="https://doi.org/10.1521/jscp.2016.35.6.501" target="_blank" class="text-indigo underline">DOI: 10.1521/jscp.2016.35.6.501</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Practice affirmations, journal, or move to express emotions, balancing with mindfulness.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Habits -->
  <section class="ebook-page distressed-bg-light" id="habits">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">📈</span>
      Habits
    </h2>
    <p class="mb-4 font-body-text">
      Small, consistent habits shape health. Challenges foster growth when approached mindfully.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Healthy habits extend life (JAMA Internal Medicine, 2018, <a href="https://doi.org/10.1001/jamainternmed.2017.8060" target="_blank" class="text-indigo underline">DOI: 10.1001/jamainternmed.2017.8060</a>).</li>
        <li>Adversity promotes growth (Psychological Bulletin, 2018, <a href="https://doi.org/10.1037/bul0000135" target="_blank" class="text-indigo underline">DOI: 10.1037/bul0000135</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Habits are hard for some (Health Psychology Review, 2020, <a href="https://doi.org/10.1080/17437199.2019.1706618" target="_blank" class="text-indigo underline">DOI: 10.1080/17437199.2019.1706618</a>).</li>
        <li>Chronic stress can harm without support (Stress and Health, 2017, <a href="https://doi.org/10.1002/smi.2746" target="_blank" class="text-indigo underline">DOI: 10.1002/smi.2746</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Start with one habit (e.g., walking) and journal challenges for growth. Seek support if needed.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Water and Intention -->
  <section class="ebook-page distressed-bg-light" id="water-intention">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">💧</span>
      Water and Intention
    </h2>
    <p class="mb-4 font-body-text">
      Water is vital, and mindful drinking can promote well-being, but claims about intention shaping its structure lack evidence.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Affirmations reduce stress (Psychoneuroendocrinology, 2018, <a href="https://doi.org/10.1016/j.psyneuen.2018.05.001" target="_blank" class="text-indigo underline">DOI: 10.1016/j.psyneuen.2018.05.001</a>).</li>
        <li>Hydration supports health (Nutrients, 2019, <a href="https://doi.org/10.3390/nu11081825" target="_blank" class="text-indigo underline">DOI: 10.3390/nu11081825</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>Emoto’s water experiments are pseudoscience (Journal of Scientific Exploration, 2008, <a href="https://doi.org/10.31275/20081553" target="_blank" class="text-indigo underline">DOI: 10.31275/20081553</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Pause to express gratitude before drinking to enhance mindfulness, not water’s structure.</p>
    </div>
    <p class="water-margin-quote">"You are water. Speak kindness."</p>
    <hr class="tribal-divider"/>
  </section>

  <!-- Baking Soda -->
  <section class="ebook-page distressed-bg-light" id="baking-soda">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">🍚</span>
      Baking Soda
    </h2>
    <p class="mb-4 font-body-text">
      Baking soda may relieve indigestion but has limited broader benefits.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <ul class="list-disc list-inside">
        <li>Neutralizes stomach acid (Alimentary Pharmacology & Therapeutics, 2020, <a href="https://doi.org/10.1111/apt.15975" target="_blank" class="text-indigo underline">DOI: 10.1111/apt.15975</a>).</li>
        <li>Reduces inflammation in some conditions (Journal of Immunology, 2018, <a href="https://doi.org/10.4049/jimmunol.1701605" target="_blank" class="text-indigo underline">DOI: 10.4049/jimmunol.1701605</a>).</li>
      </ul>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <ul class="list-disc list-inside">
        <li>No evidence for cold/flu or gut balance benefits.</li>
        <li>Overuse risks alkalosis (American Journal of Emergency Medicine, 2019, <a href="https://doi.org/10.1016/j.ajem.2018.10.039" target="_blank" class="text-indigo underline">DOI: 10.1016/j.ajem.2018.10.039</a>).</li>
      </ul>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Use sparingly for indigestion. Consult a doctor for other uses.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- Wholeness -->
  <section class="ebook-page distressed-bg-light" id="wholeness">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
      <span class="mr-4 text-5xl">✨</span>
      Wholeness
    </h2>
    <p class="mb-4 font-body-text">
      Health integrates body, mind, and connections. Tailor practices to your needs.
    </p>
    <div class="info-box science">
      <h3>Science:</h3>
      <p>The biopsychosocial model supports holistic health (Lancet, 2017, <a href="https://doi.org/10.1016/S0140-6736(17)31071-6" target="_blank" class="text-indigo underline">DOI: 10.1016/S0140-6736(17)31071-6</a>).</p>
    </div>
    <div class="info-box contrary">
      <h3>Contrary View:</h3>
      <p>Ancestral practices may not suit all (American Journal of Public Health, 2020, <a href="https://doi.org/10.2105/AJPH.2020.305837" target="_blank" class="text-indigo underline">DOI: 10.2105/AJPH.2020.305837</a>).</p>
    </div>
    <div class="info-box advice">
      <h3>Advice:</h3>
      <p>Experiment and personalize with professional guidance.</p>
    </div>
    <hr class="tribal-divider"/>
  </section>

  <!-- You CAN - Closing Spread -->
  <section class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white" id="you-can">
    <h2 class="text-5xl font-main-title text-gold-foil mb-8 tracking-wider">YOU CAN</h2>
    <div class="my-6 w-[250px] h-[180px] mx-auto">
      <!-- Closing SVG omitted for brevity, include your SVG here if needed -->
    </div>
    <p class="text-2xl font-body-text mb-6">
      You can enhance health with evidence-based practices.
    </p>
    <ul class="list-none text-xl font-subtitle-font space-y-3">
      <li><span class="text-gold-foil text-3xl">&bull;</span> Start small.</li>
      <li><span class="text-gold-foil text-3xl">&bull;</span> Stay curious.</li>
      <li><span class="text-gold-foil text-3xl">&bull;</span> Balance tradition with science.</li>
    </ul>
    <p class="text-lg font-subtitle-font italic mt-8 text-soft-white/80">
      Your journey to wholeness begins.
    </p>
  </section>

  <!-- Summary Table -->
  <section class="ebook-page distressed-bg-light" id="summary-table">
    <h2 class="text-4xl font-section-header text-terracotta mb-6 text-center">Summary Table</h2>
    <div class="grid grid-cols-1 gap-6 font-body-text bg-charcoal-black p-4 rounded-xl shadow-inner text-soft-white">
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Raw Meat</h3>
        <p class="text-sm"><strong>Claim:</strong> Boosts vitality</p>
        <p class="text-sm"><strong>Support:</strong> Partial: Nutrient retention</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> High risks, unproven benefits</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Morning Sunlight</h3>
        <p class="text-sm"><strong>Claim:</strong> Improves health</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Resets rhythm</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Access, sensitivity issues</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Circadian Rhythm</h3>
        <p class="text-sm"><strong>Claim:</strong> Aligns body clocks</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Metabolic, mood benefits</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Shift work, genetics</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Contrast Therapy</h3>
        <p class="text-sm"><strong>Claim:</strong> Recovery, resilience</p>
        <p class="text-sm"><strong>Support:</strong> Moderate: Recovery, some mental health</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Heart risk, weak evidence for “reset”</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Relationships</h3>
        <p class="text-sm"><strong>Claim:</strong> Heal, thrive</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Longevity, immunity</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Some thrive solo</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Self-Compassion</h3>
        <p class="text-sm"><strong>Claim:</strong> Reduces stress</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Mental, physical health</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Over-expression risk</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Habits</h3>
        <p class="text-sm"><strong>Claim:</strong> Shape health</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Longevity, growth</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Stress, difficulty</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Water & Intention</h3>
        <p class="text-sm"><strong>Claim:</strong> Mindful drinking heals</p>
        <p class="text-sm"><strong>Support:</strong> Partial: Mindfulness, hydration</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> No evidence for water structure</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Baking Soda</h3>
        <p class="text-sm"><strong>Claim:</strong> Gut, inflammation aid</p>
        <p class="text-sm"><strong>Support:</strong> Partial: Indigestion, some inflammation</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Overuse risks, limited scope</p>
      </div>
      <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
        <h3 class="text-xl font-subtitle-font text-gold-foil">Wholeness</h3>
        <p class="text-sm"><strong>Claim:</strong> Integrates health</p>
        <p class="text-sm"><strong>Support:</strong> Strong: Biopsychosocial model</p>
        <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Not one-size-fits-all</p>
      </div>
    </div>
  </section>

  <!-- Back to Top Button -->
  <button id="backToTop" title="Back to Top">↑ Top</button>
  <script>
    // Show/hide back to top button
    const backToTop = document.getElementById('backToTop');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 400) {
        backToTop.classList.add('show');
      } else {
        backToTop.classList.remove('show');
      }
    });
    backToTop.addEventListener('click', () => {
      window.scrollTo({top: 0, behavior: 'smooth'});
    });
  </script>
</body>
</html>
