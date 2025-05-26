# 🧠 HTML Semantiska Element, Cheatsheet

## 📚 Vad betyder "semantiska element"?
Semantiska HTML-element beskriver tydligt *vad innehållet är*, både för webbläsare och utvecklare – till skillnad från bara *hur det ser ut*. Det förbättrar tillgänglighet, SEO och kodens struktur.

---

## 🏛️ Struktur-element

| Element | Beskrivning |
|--------|-------------|
| `<header>`   | Innehåller introduktion eller navigering – vanligtvis sidhuvud. |
| `<nav>`      | Innehåller navigeringslänkar. |
| `<main>`     | Huvudinnehållet för sidan (endast ett `<main>` per sida). |
| `<section>`  | En logisk sektion av innehåll, t.ex. en artikel-del eller kapitel. |
| `<article>`  | Självständigt innehåll, t.ex. en bloggpost eller nyhetsartikel. |
| `<aside>`    | Komplement till huvudinnehållet – t.ex. en sidokolumn. |
| `<footer>`   | Innehåller sidfot – kontaktinfo, copyright etc. |

---

## 📝 Text & innehåll

| Element | Beskrivning |
|---------|-------------|
| `<h1>`–`<h6>` | Rubriker där `<h1>` är viktigast, `<h6>` minst viktig. |
| `<p>`         | Ett stycke text. |
| `<strong>`    | Viktigt innehåll (betonas semantiskt). |
| `<em>`        | Betonat innehåll (kursivt med betydelse). |
| `<blockquote>`| Ett citat från annan källa. |
| `<q>`         | In-line citat. |
| `<abbr>`      | Förkortning, med möjlighet till förklaring i `title`. |
| `<time>`      | Anger ett datum eller tid (kan tolkas av maskiner). |

---

## 🔗 Länkar & media

| Element | Beskrivning |
|---------|-------------|
| `<a>`           | Länk till annan sida eller sektion. |
| `<img>`         | Bild (kom ihåg `alt` för tillgänglighet!). |
| `<figure>`      | Innehåller media med en beskrivning. |
| `<figcaption>`  | Beskrivning av innehållet i `<figure>`. |
| `<audio>`       | Ljudfil. |
| `<video>`       | Videoinnehåll. |

---

## 🧾 Listor & tabeller

| Element | Beskrivning |
|---------|-------------|
| `<ul>`          | Oordnad lista (punkter). |
| `<ol>`          | Ordnad lista (nummer). |
| `<li>`          | Lista-element (används i både `<ul>` och `<ol>`). |
| `<dl>`          | Beskrivningslista. |
| `<dt>`          | Term som ska beskrivas. |
| `<dd>`          | Beskrivning av termen. |
| `<table>`       | Tabellbehållare. |
| `<thead>`       | Rubrik-rad(er). |
| `<tbody>`       | Innehållsrader. |
| `<tfoot>`       | Sammanfattande rad(er), t.ex. totalsumma. |
| `<tr>`          | Tabellrad. |
| `<th>`          | Rubrikcell. |
| `<td>`          | Datacell. |

---

## 📦 Formulär

| Element | Beskrivning |
|---------|-------------|
| `<form>`       | Samlar formulärelement. |
| `<label>`      | Etikett för ett inputfält (kopplas via `for`-attribut). |
| `<input>`      | Inmatningsfält (text, email, checkbox, etc.). |
| `<textarea>`   | Fler-radigt textfält. |
| `<select>`     | Rullgardinsmeny. |
| `<option>`     | Värde i select. |
| `<button>`     | Klickbar knapp. |
| `<fieldset>`   | Grupperar relaterade fält. |
| `<legend>`     | Rubrik för en `<fieldset>`. |

---

## 🪧 Landmarks

| **Landmark**       | **HTML5-tagg**          | **ARIA-roll (om HTML-tagg saknas)** |
| ------------------ | ----------------------- | ----------------------------------- |
| Main content       | `<main>`                | `role="main"`                       |
| Navigation         | `<nav>`                 | `role="navigation"`                 |
| Header             | `<header>`              | `role="banner"`                     |
| Footer             | `<footer>`              | `role="contentinfo"`                |
| Search             | (t.ex. `<form>`)        | `role="search"`                     |
| Complementary info | `<aside>`               | `role="complementary"`              |
| Region/section     | `<section>` (med titel) | `role="region"`                     |

---

## ✅ Tips för tillgänglighet & god semantik
- **Använd `alt` på bilder** – kortfattad och beskrivande text.
- **Rubriknivåer ska vara hierarkiska** – t.ex. `h1` → `h2` → `h3`.
- **Undvik `<div>` och `<span>`** när semantiska alternativ finns.
- **Använd `<label>` med `for`** för alla formulärfält.
- **Sätt `lang="sv"` i `<html>`** för att visa att sidan är på svenska.
- **Testa med skärmläsare** eller tillgänglighetsverktyg som Lighthouse.

---

