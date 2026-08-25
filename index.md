---
layout: splash
title: "CLIMATE Research Group"
excerpt: "Chemical Looping for Industrial Materials, Aviation Transition & Thermochemical Energy Systems"

header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.30
  overlay_color: "#003049"
  overlay_logo: /assets/images/logo.png
  overlay_logo_height: 240
  classes: wide
---


<div class="fade-in" style="text-align:center; padding: 40px 0;">

  <img src="/assets/images/logo.png" alt="CLIMATE Crest Logo" width="660" class="fade-up" style="margin-bottom:20px;">

  <h1 class="fade-up" style="font-size:2.2em; margin-bottom:10px; font-weight:600;">
    CLIMATE Research Group
  </h1>

  <p class="fade-up" style="font-size:1.2em; max-width:700px; margin:auto; line-height:1.6;">
    Developing next‑generation technologies for CO₂ utilisation, chemical looping, hydrogen production,
    and sustainable fuel pathways through advanced materials, reactor engineering, and computational modelling.
  </p>

  <div class="fade-up" style="margin-top:25px;">
    <a href="/research/" class="btn btn--primary" style="margin-right:10px;">Research</a>
    <a href="/projects/" class="btn btn--info" style="margin-right:10px;">Projects</a>
    <a href="/people/" class="btn btn--success">Team</a>
  </div>

</div>

---

## 🔬 Our Research Pillars

<div class="research-grid fade-in">
  <div class="rg-item lift">
    <h3>🔥 Chemical Looping</h3>
    <p>Redox systems for H₂ production, CO₂ capture, and syngas generation.</p>
  </div>

  <div class="rg-item lift">
    <h3>🧪 Materials</h3>
    <p>Perovskites, ceria carriers, catalysts, and sorbents for high‑temperature processes.</p>
  </div>

  <div class="rg-item lift">
    <h3>⚙️ Modelling</h3>
    <p>Reactor modelling, ANN‑enhanced kinetics, and Aspen Plus® process simulation.</p>
  </div>

  <div class="rg-item lift">
    <h3>🌱 CO₂ Utilisation</h3>
    <p>RWGS‑CL syngas pathways, FT synthesis, and sustainable aviation fuel integration.</p>
  </div>
</div>

---

## 👥 People
Meet the researchers driving innovation in thermochemical engineering.

👉 **[People](ca://s?q=Open_People_page)**

---

## 📚 Publications
Explore our journal articles, conference papers, theses, and preprints.

👉 **[Publications](ca://s?q=Open_Publications_page)**

---

## 📬 Contact
For collaborations or enquiries, reach out via email or visit our laboratory.

👉 **[Contact](ca://s?q=Open_Contact_page)**

---

<style>

/* --- Fade-in animation --- */
.fade-in {
  animation: fadeIn 1.2s ease-out forwards;
  opacity: 0;
}

.fade-up {
  animation: fadeUp 1.2s ease-out forwards;
  opacity: 0;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to   { opacity: 1; }
}

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(25px); }
  to   { opacity: 1; transform: translateY(0); }
}

/* --- Research grid --- */
.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 22px;
  margin: 30px 0;
}

/* --- Card hover lift animation --- */
.rg-item {
  background: #fafafa;
  padding: 18px 22px;
  border-radius: 10px;
  border: 1px solid #e5e5e5;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.rg-item:hover {
  transform: translateY(-6px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.12);
}

.lift {
  animation: fadeUp 1.2s ease-out forwards;
  opacity: 0;
}

</style>
