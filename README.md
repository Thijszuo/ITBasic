# Portfolio Website

Mijn persoonlijke portfolio-website met een overzicht van de vijf vakken die ik momenteel volg op school, plus een pagina met de projecten die ik zelf heb gebouwd.

## Vakken

| Vak | Wat ik leer |
|-----|-------------|
| **Python** | Programmeren in Python. Variabelen, functies, loops en het werken met bibliotheken. |
| **Frontend** | HTML, CSS en JavaScript. Het bouwen van responsieve websites met moderne technieken. |
| **Backend** | Server-side programmeren, API's maken en werken met externe diensten. |
| **IT Basic (AI)** | De basis van kunstmatige intelligentie leren begrijpen en toepassen. |
| **Database** | Databases ontwerpen, SQL queries schrijven en data beheren. |

## Structuur

```
Week 2/
├── index.html          # Hoofdpagina
├── projecten.html      # Pagina met mijn projecten
├── README.md           # Deze bestand
├── css/
│   └── style.css       # Stijlen
├── js/
│   └── script.js       # Functionaliteit
└── images/             # Afbeeldingen
```

## Functies

- Responsief ontwerp (mobiel-vriendelijk)
- Navigatiemenu met hamburger op mobiel
- Secties: Home, Over mij, Vakken, Contact
- Contactformulier
- Scroll-animaties
- Projectenpagina met kaarten per project: screenshot, beschrijving, technieken en mijn rol

## Projecten

Op `projecten.html` staan drie projecten:

| Project | Technieken |
|---------|-----------|
| **Pythonspel** | Python, JSON |
| **Persoonlijk dashboard** | HTML, CSS, JavaScript |
| **Boeken-database** | SQL, Python |

Elke kaart toont een screenshot uit de `images/` map. De afbeelding vult het 16:9-vak en wordt
bij een ander formaat automatisch bijgesneden (`object-fit: cover`). Om een andere afbeelding te
gebruiken, wissel je de `src` in `<div class="project-shot">`.

## Gebruik

Open `index.html` in je browser om de website te bekijken.

## Aanpassingen

- Wijzig je naam in `index.html`
- Pas de kleuren aan in `css/style.css` (CSS variabelen bovenaan)
- Voeg afbeeldingen toe aan de `images/` map
=