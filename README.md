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
        /* Custom Color Palette */
        :root {
            --color-sandstone: #E3C0A0; /* Primary background for light pages */
            --color-terracotta: #A52A2A; /* Main accent red */
            --color-indigo: #4B0082; /* Main accent blue/purple */
            --color-gold-foil: #D4AF37; /* Gold accent */
            --color-charcoal-black: #333333; /* For text and dark backgrounds */
            --color-soft-white: #F8F8F8; /* For light text on dark backgrounds */
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

        /* Font Styles */
        .font-main-title { font-family: 'Bebas Neue', sans-serif; letter-spacing: 0.05em; }
        .font-subtitle-font { font-family: 'Lora', serif; } /* Using Lora for the subtitle */
        .font-body-text { font-family: 'Lora', serif; } /* Modern serif for body */
        .font-section-header { font-family: 'Pacifico', cursive; }

        /* General Page Container - Adjusted for no text cutoff */
        .ebook-page {
            width: 100%;
            max-width: 800px; /* Standard ebook width for readability */
            margin: 2rem auto;
            border: 1px solid rgba(0,0,0,0.05);
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            position: relative;
            border-radius: 0.5rem;
            display: flex;
            flex-direction: column;
            padding: 2rem;
            /* Removed min-height and aspect-ratio here to allow content to dictate height */
        }
        @media (min-width: 768px) {
            .ebook-page {
                padding: 3rem;
            }
        }

        /* Distressed Background Effect (Tribal motif) */
        .distressed-bg-light {
            background-color: var(--color-sandstone);
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="10" cy="10" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="50" cy="50" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="90" cy="90" r="2" fill="%23A52A2A" opacity="0.1"/><circle cx="10" cy="90" r="2" fill="%234B0082" opacity="0.05"/><circle cx="90" cy="10" r="2" fill="%234B0082" opacity="0.05"/></svg>');
            background-size: 50px 50px; /* Adjust size of dots */
            background-repeat: repeat;
        }

        .distressed-bg-dark {
            background-color: var(--color-charcoal-black);
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><circle cx="10" cy="10" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="50" cy="50" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="90" cy="90" r="2" fill="%23E3C0A0" opacity="0.1"/><circle cx="10" cy="90" r="2" fill="%23D4AF37" opacity="0.05"/><circle cx="90" cy="10" r="2" fill="%23D4AF37" opacity="0.05"/></svg>');
            background-size: 50px 50px;
            background-repeat: repeat;
        }

        /* Info Boxes */
        .info-box {
            padding: 0.75rem 1rem;
            border-radius: 0.5rem;
            margin-top: 1rem;
            font-size: 0.9rem;
            line-height: 1.4;
            border-left-width: 4px;
        }
        .info-box.science {
            background-color: rgba(165, 42, 42, 0.1); /* Light terracotta */
            border-color: var(--color-terracotta);
            color: var(--color-charcoal-black);
        }
        .info-box.contrary {
            background-color: rgba(75, 0, 130, 0.1); /* Light indigo */
            border-color: var(--color-indigo);
            color: var(--color-charcoal-black);
        }
        .info-box.advice {
            background-color: rgba(212, 175, 55, 0.1); /* Light gold */
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

        /* Pull Quotes */
        .pull-quote {
            font-family: 'Pacifico', cursive;
            font-size: 1.75rem;
            line-height: 1.3;
            padding: 1rem;
            margin: 1.5rem 0;
            text-align: center;
            color: var(--color-gold-foil);
            background-color: rgba(255, 255, 255, 0.05); /* Very subtle overlay */
            border-radius: 0.5rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        /* Tribal Divider */
        .tribal-divider {
            border: none;
            border-top: 2px dashed rgba(0,0,0,0.3); /* Simpler dashed line */
            margin: 2rem 0;
            width: 80%;
            opacity: 0.7;
        }

        /* Water Margin Quote */
        .water-margin-quote {
            font-family: 'Lora', serif;
            font-style: italic;
            font-size: 1.1rem;
            text-align: right;
            margin-top: 2rem;
            padding: 0.5rem 1rem;
            background-color: rgba(75, 0, 130, 0.05); /* Light indigo background */
            color: var(--color-indigo);
            border-radius: 0.25rem;
        }

        /* SVG Icon for chapter openers */
        .chapter-icon {
            flex-shrink: 0; /* Prevent icon from shrinking */
            width: 40px;
            height: 40px;
        }
    </style>
</head>
<body class="bg-gray-100 font-body-text text-charcoal-black">

    <!-- Cover Page -->
    <div class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center">
        <div class="relative z-10 flex flex-col items-center">
            <h1 class="text-7xl md:text-9xl font-main-title leading-none mb-4 text-gold-foil drop-shadow-lg tracking-wider">
                RAW
            </h1>
            <h2 class="text-4xl md:text-5xl font-subtitle-font leading-tight mb-6 text-soft-white tracking-wide">
                Reconnect And Wake
            </h2>
            <!-- Symbolic image inspired by cover art -->
            <div class="my-6 w-[200px] h-[150px]">
                <svg width="100%" height="100%" viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
                    <!-- Sound Waves (Gold) -->
                    <path d="M0 75 C 20 55, 40 95, 60 75 S 80 55, 100 75 S 120 95, 140 75 S 160 55, 180 75" stroke="#D4AF37" stroke-width="2" fill="none"/>
                    <path d="M200 75 C 180 55, 160 95, 140 75 S 120 55, 100 75 S 80 95, 60 75 S 40 55, 20 75" stroke="#D4AF37" stroke-width="2" fill="none"/>
                    <!-- Sun (Terracotta/Gold) -->
                    <circle cx="100" cy="75" r="40" fill="#A52A2A"/>
                    <circle cx="100" cy="75" r="20" fill="#D4AF37"/>
                    <!-- Sun Rays -->
                    <line x1="100" y1="30" x2="100" y2="45" stroke="#D4AF37" stroke-width="2"/>
                    <line x1="115" y1="35" x2="125" y2="45" stroke="#D4AF37" stroke-width="2" transform="rotate(30 100 75)"/>
                    <line x1="130" y1="50" x2="140" y2="60" stroke="#D4AF37" stroke-width="2" transform="rotate(60 100 75)"/>
                    <line x1="135" y1="75" x2="145" y2="75" stroke="#D4AF37" stroke-width="2" transform="rotate(90 100 75)"/>
                    <line x1="130" y1="100" x2="140" y2="90" stroke="#D4AF37" stroke-width="2" transform="rotate(120 100 75)"/>
                    <line x1="115" y1="115" x2="125" y2="105" stroke="#D4AF37" stroke-width="2" transform="rotate(150 100 75)"/>
                    <line x1="100" y1="120" x2="100" y2="105" stroke="#D4AF37" stroke-width="2" transform="rotate(180 100 75)"/>
                    <line x1="85" y1="115" x2="75" y2="105" stroke="#D4AF37" stroke-width="2" transform="rotate(210 100 75)"/>
                    <line x1="70" y1="100" x2="60" y2="90" stroke="#D4AF37" stroke-width="2" transform="rotate(240 100 75)"/>
                    <line x1="65" y1="75" x2="55" y2="75" stroke="#D4AF37" stroke-width="2" transform="rotate(270 100 75)"/>
                    <line x1="70" y1="50" x2="60" y2="60" stroke="#D4AF37" stroke-width="2" transform="rotate(300 100 75)"/>
                    <line x1="85" y1="35" x2="75" y2="45" stroke="#D4AF37" stroke-width="2" transform="rotate(330 100 75)"/>
                    <!-- Wave (Indigo) -->
                    <path d="M60 90 C 80 110, 120 110, 140 90 L 140 150 L 60 150 Z" fill="#4B0082"/>
                    <path d="M65 95 C 80 110, 120 110, 135 95" stroke="white" stroke-width="2" fill="none"/>
                    <!-- Heart -->
                    <path d="M100 65 L 95 60 C 92 57, 88 57, 85 60 C 82 63, 82 67, 85 70 L 100 85 L 115 70 C 118 67, 118 63, 115 60 C 112 57, 108 57, 105 60 L 100 65 Z" fill="#A52A2A"/>
                </svg>
            </div>
            <p class="text-xl md:text-2xl font-body-text mt-6 text-soft-white opacity-90">
                A science-informed guide to raw nourishment, circadian rhythm, contrast therapy, emotional well-being, and connection, blending ancestral wisdom with modern evidence.
            </p>
            <p class="text-lg font-subtitle-font italic mt-4 text-soft-white">
                Speak Love to Your Life
            </p>
        </div>
    </div>

    <!-- Back Cover / Overall Blurb -->
    <div class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white">
        <div class="relative z-10 p-6">
            <h3 class="text-3xl font-subtitle-font mb-8">
                "A science-informed guide to ancestral rhythms and modern well-being."
            </h3>
            <!-- Sun-wave symbol fading into soundwaves -->
            <div class="my-8 w-[250px] h-[180px] mx-auto opacity-70">
                <svg width="100%" height="100%" viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
                    <!-- Sound Waves (Gold) - more subtle -->
                    <path d="M0 75 C 20 55, 40 95, 60 75 S 80 55, 100 75 S 120 95, 140 75 S 160 55, 180 75" stroke="#D4AF37" stroke-width="1" opacity="0.6" fill="none"/>
                    <path d="M200 75 C 180 55, 160 95, 140 75 S 120 55, 100 75 S 80 95, 60 75 S 40 55, 20 75" stroke="#D4AF37" stroke-width="1" opacity="0.6" fill="none"/>
                    <!-- Sun (Terracotta/Gold) - fading -->
                    <circle cx="100" cy="75" r="40" fill="#A52A2A" opacity="0.4"/>
                    <circle cx="100" cy="75" r="20" fill="#D4AF37" opacity="0.4"/>
                    <!-- Sun Rays -->
                    <line x1="100" y1="30" x2="100" y2="45" stroke="#D4AF37" stroke-width="1" opacity="0.4"/>
                    <line x1="115" y1="35" x2="125" y2="45" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(30 100 75)"/>
                    <line x1="130" y1="50" x2="140" y2="60" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(60 100 75)"/>
                    <line x1="135" y1="75" x2="145" y2="75" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(90 100 75)"/>
                    <line x1="130" y1="100" x2="140" y2="90" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(120 100 75)"/>
                    <line x1="115" y1="115" x2="125" y2="105" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(150 100 75)"/>
                    <line x1="100" y1="120" x2="100" y2="105" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(180 100 75)"/>
                    <line x1="85" y1="115" x2="75" y2="105" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(210 100 75)"/>
                    <line x1="70" y1="100" x2="60" y2="90" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(240 100 75)"/>
                    <line x1="65" y1="75" x2="55" y2="75" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(270 100 75)"/>
                    <line x1="70" y1="50" x2="60" y2="60" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(300 100 75)"/>
                    <line x1="85" y1="35" x2="75" y2="45" stroke="#D4AF37" stroke-width="1" opacity="0.4" transform="rotate(330 100 75)"/>
                    <!-- Wave (Indigo) - fading -->
                    <path d="M60 90 C 80 110, 120 110, 140 90 L 140 150 L 60 150 Z" fill="#4B0082" opacity="0.4"/>
                    <path d="M65 95 C 80 110, 120 110, 135 95" stroke="white" stroke-width="1" opacity="0.4" fill="none"/>
                    <!-- Heart -->
                    <path d="M100 65 L 95 60 C 92 57, 88 57, 85 60 C 82 63, 82 67, 85 70 L 100 85 L 115 70 C 118 67, 118 63, 115 60 C 112 57, 108 57, 105 60 L 100 65 Z" fill="#A52A2A" opacity="0.4"/>
                </svg>
            </div>
            <p class="text-xl font-body-text mt-4 opacity-80">
                Dive deep into ancestral wisdom, backed by modern science, to reconnect with your natural rhythms and embrace a balanced, thriving life.
            </p>
        </div>
    </div>

    <!-- Introduction -->
    <div class="ebook-page distressed-bg-light">
        <h2 class="text-4xl font-section-header text-terracotta mb-6 flex items-center">
            <span class="mr-4 chapter-icon">
                <svg width="100%" height="100%" viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="100" cy="75" r="40" fill="#A52A2A"/>
                    <circle cx="100" cy="75" r="20" fill="#D4AF37"/>
                    <path d="M65 95 C 80 110, 120 110, 135 95" stroke="#4B0082" stroke-width="4" fill="none"/>
                </svg>
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
    </div>

    <!-- Raw Meat – Nourishment with Caution -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Morning Sunlight -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Circadian Rhythm -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Contrast Therapy -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Relationships -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Self-Compassion -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Habits -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Water and Intention -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Baking Soda -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- Wholeness -->
    <div class="ebook-page distressed-bg-light">
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
    </div>

    <!-- You CAN - Closing Spread -->
    <div class="ebook-page distressed-bg-dark flex flex-col justify-center items-center text-center text-soft-white">
        <h2 class="text-5xl font-main-title text-gold-foil mb-8 tracking-wider">YOU CAN</h2>
        <div class="my-6 w-[250px] h-[180px] mx-auto">
             <svg width="100%" height="100%" viewBox="0 0 200 150" fill="none" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
                <!-- Lightning Bolt (Gold) -->
                <path d="M70 10 L 130 10 L 100 80 L 130 80 L 70 140 L 100 70 L 70 70 Z" fill="#D4AF37" stroke="#A52A2A" stroke-width="2"/>
                <!-- Heart (Terracotta) -->
                <path d="M140 30 L 135 25 C 132 22, 128 22, 125 25 C 122 28, 122 32, 125 35 L 140 50 L 155 35 C 158 32, 158 28, 155 60 C 152 22, 148 22, 145 25 L 140 30 Z" fill="#A52A2A" stroke="#D4AF37" stroke-width="2"/>
            </svg>
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
    </div>

    <!-- Summary Table -->
    <div class="ebook-page distressed-bg-light">
        <h2 class="text-4xl font-section-header text-terracotta mb-6 text-center">Summary Table</h2>
        <div class="grid grid-cols-1 gap-6 font-body-text bg-charcoal-black p-4 rounded-xl shadow-inner text-soft-white">
            <!-- Table Headers (visible only on larger screens if desired, removed for simplicity here as rows contain labels) -->

            <!-- Table Rows (Each row is a flex container for better mobile stacking) -->
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
                <p class="text-sm"><strong>Claim:</strong> Enhances energy</p>
                <p class="text-sm"><strong>Support:</strong> Strong: Metabolic benefits</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Genetic, lifestyle barriers</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Contrast Therapy</h3>
                <p class="text-sm"><strong>Claim:</strong> Aids recovery</p>
                <p class="text-sm"><strong>Support:</strong> Partial: Blood flow benefits</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Limited nervous system evidence</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Relationships</h3>
                <p class="text-sm"><strong>Claim:</strong> Promotes healing</p>
                <p class="text-sm"><strong>Support:</strong> Strong: Oxytocin benefits</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Introvert needs differ</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Self-Compassion</h3>
                <p class="text-sm"><strong>Claim:</strong> Supports health</p>
                <p class="text-sm"><strong>Support:</strong> Strong: Lowers anxiety</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Over-expression risks</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Habits</h3>
                <p class="text-sm"><strong>Claim:</strong> Shapes well-being</p>
                <p class="text-sm"><strong>Support:</strong> Strong: Extends life</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Hard to form for some</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Water + Intention</h3>
                <p class="text-sm"><strong>Claim:</strong> Intention shapes health</p>
                <p class="text-sm text-gold-foil"><strong>Support:</strong> None: Pseudoscience</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Affirmations help mood</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Baking Soda</h3>
                <p class="text-sm"><strong>Claim:</strong> Aids digestion, illness</p>
                <p class="text-sm"><strong>Support:</strong> Partial: Indigestion relief</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Limited broader evidence</p>
            </div>
            <div class="flex flex-col gap-2 p-4 bg-indigo/70 rounded-lg shadow-md col-span-full border border-gold-foil">
                <h3 class="text-xl font-subtitle-font text-gold-foil">Wholeness + 'You CAN'</h3>
                <p class="text-sm"><strong>Claim:</strong> Health integrates body, mind, and connections.</p>
                <p class="text-sm"><strong>Support:</strong> The biopsychosocial model supports holistic health.</p>
                <p class="text-sm text-terracotta"><strong>Contrary View:</strong> Ancestral practices may not suit all.</p>
            </div>
        </div>
    </div>

</body>
</html>