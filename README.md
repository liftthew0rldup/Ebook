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
            font-size: 0.9rem;
            line-height: 1.4;
            border-left-width: 4px;
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
        .info-box h3 { font-weight: 700; margin-bottom: 0.25rem; }
        .info-box ul { list-style: disc; padding-left: 1.25rem; }
        .info-box ul li { margin-bottom: 0.1rem; }
        .pull-quote {
            font-family: 'Pacifico', cursive;
            font-size: 1.75rem;
            line-height: 1.3;
            padding: 1rem;
            margin: 1.5rem 0;
            text-align: center;
            color: var(--color-gold-foil);
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 0.5rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
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
        /* Table of Contents Styling */
        .toc-link { transition: color 0.2s; }
        .toc-link:hover { color: var(--color-gold-foil); }
    </style>
</head>
<body class="bg-gray-100 font-body-text text-charcoal-black">
<main>
    <!-- Navigation / Table of Contents -->
    <nav aria-label="Table of Contents" class="ebook-page distressed-bg-light mb-4">
        <header>
            <h2 class="text-2xl font-main-title text-terracotta mb-2">Contents</h2>
        </header>
        <ol class="list-decimal ml-6 space-y-1 text-lg">
            <li><a href="#introduction" class="toc-link text-indigo underline">Introduction</a></li>
            <li><a href="#raw-meat" class="toc-link text-indigo underline">Raw Meat – Nourishment with Caution</a></li>
            <li><a href="#morning-sunlight" class="toc-link text-indigo underline">Morning Sunlight</a></li>
            <li><a href="#circadian-rhythm" class="toc-link text-indigo underline">Circadian Rhythm</a></li>
            <li><a href="#contrast-therapy" class="toc-link text-indigo underline">Contrast Therapy</a></li>
            <li><a href="#relationships" class="toc-link text-indigo underline">Relationships</a></li>
            <li><a href="#self-compassion" class="toc-link text-indigo underline">Self-Compassion</a></li>
            <li><a href="#habits" class="toc-link text-indigo underline">Habits</a></li>
            <li><a href="#water-intention" class="toc-link text-indigo underline">Water and Intention</a></li>
            <li><a href="#baking-soda" class="toc-link text-indigo underline">Baking Soda</a></li>
            <li><a href="#wholeness" class="toc-link text-indigo underline">Wholeness</a></li>
            <li><a href="#you-can" class="toc-link text-indigo underline">You CAN</a></li>
            <li><a href="#summary-table" class="toc-link text-indigo underline">Summary Table</a></li>
        </ol>
    </nav>

    <!-- Cover Page -->
    <section class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center" aria-label="Cover">
        <div class="relative z-10 flex flex-col items-center">
            <h1 class="text-7xl md:text-9xl font-main-title leading-none mb-4 text-gold-foil drop-shadow-lg tracking-wider">
                RAW
            </h1>
            <h2 class="text-4xl md:text-5xl font-subtitle-font leading-tight mb-6 text-soft-white tracking-wide">
                Reconnect And Wake
            </h2>
            <div class="my-6 w-[200px] h-[150px]" aria-hidden="true">
                <!-- SVG omitted for brevity, keep as in your original -->
            </div>
            <p class="text-xl md:text-2xl font-body-text mt-6 text-soft-white opacity-90">
                A science-informed guide to raw nourishment, circadian rhythm, contrast therapy, emotional well-being, and connection, blending ancestral wisdom with modern evidence.
            </p>
            <p class="text-lg font-subtitle-font italic mt-4 text-soft-white">
                Speak Love to Your Life
            </p>
        </div>
    </section>

    <!-- Back Cover / Overall Blurb -->
    <section class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white" aria-label="Back Cover">
        <div class="relative z-10 p-6">
            <h3 class="text-3xl font-subtitle-font mb-8">
                "A science-informed guide to ancestral rhythms and modern well-being."
            </h3>
            <div class="my-8 w-[250px] h-[180px] mx-auto opacity-70" aria-hidden="true">
                <!-- SVG omitted for brevity, keep as in your original -->
            </div>
            <p class="text-xl font-body-text mt-4 opacity-80">
                Dive deep into ancestral wisdom, backed by modern science, to reconnect with your natural rhythms and embrace a balanced, thriving life.
            </p>
        </div>
    </section>

    <!-- Each Chapter Section -->
    <section id="introduction" class="ebook-page distressed-bg-light" aria-labelledby="introduction-header">
        <h2 id="introduction-header" class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
            <span class="mr-4 chapter-icon" aria-hidden="true">
                <!-- SVG omitted for brevity -->
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
    <!-- Repeat for each section, using the same pattern and unique IDs for anchor navigation -->
    <!-- ... -->
    <section id="raw-meat" class="ebook-page distressed-bg-light" aria-labelledby="raw-meat-header">
        <!-- ... -->
    </section>
    <section id="morning-sunlight" class="ebook-page distressed-bg-light" aria-labelledby="morning-sunlight-header">
        <!-- ... -->
    </section>
    <section id="circadian-rhythm" class="ebook-page distressed-bg-light" aria-labelledby="circadian-rhythm-header">
        <!-- ... -->
    </section>
    <section id="contrast-therapy" class="ebook-page distressed-bg-light" aria-labelledby="contrast-therapy-header">
        <!-- ... -->
    </section>
    <section id="relationships" class="ebook-page distressed-bg-light" aria-labelledby="relationships-header">
        <!-- ... -->
    </section>
    <section id="self-compassion" class="ebook-page distressed-bg-light" aria-labelledby="self-compassion-header">
        <!-- ... -->
    </section>
    <section id="habits" class="ebook-page distressed-bg-light" aria-labelledby="habits-header">
        <!-- ... -->
    </section>
    <section id="water-intention" class="ebook-page distressed-bg-light" aria-labelledby="water-intention-header">
        <!-- ... -->
    </section>
    <section id="baking-soda" class="ebook-page distressed-bg-light" aria-labelledby="baking-soda-header">
        <!-- ... -->
    </section>
    <section id="wholeness" class="ebook-page distressed-bg-light" aria-labelledby="wholeness-header">
        <!-- ... -->
    </section>
    <section id="you-can" class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white" aria-labelledby="you-can-header">
        <!-- ... -->
    </section>

    <!-- Summary Table -->
    <section id="summary-table" class="ebook-page distressed-bg-light" aria-labelledby="summary-table-header">
        <h2 id="summary-table-header" class="text-4xl font-section-header text-terracotta mb-6 text-center">Summary Table</h2>
        <div class="grid grid-cols-1 gap-6 font-body-text bg-charcoal-black p-4 rounded-xl shadow-inner text-soft-white">
            <!-- Each row as in previous message, see above for code -->
            <!-- ... -->
        </div>
    </section>
</main>
<footer class="w-full text-center py-6 bg-charcoal-black text-soft-white font-subtitle-font text-lg">
    &copy; 2025 Reconnect & Wake. All rights reserved.
</footer>
</body>
</html>
