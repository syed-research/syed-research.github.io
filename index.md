---
layout: splash
title: "CLIMATE Research Group"
excerpt: "Chemical Looping for Industrial Materials, Aviation Transition & Thermochemical Energy Systems"

header:
  overlay_image: /assets/images/Banner.jpg
  overlay_filter: 0.60
  overlay_logo: /assets/images/logo.png
  overlay_logo_height: 100
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
   <a href="/facilities/" class="btn btn--primary">Facilities</a>
    <a href="/people/" class="btn btn--success">Team</a>
  </div>

</div>

---

## 🔬 Our Research Pillars

<div class="research-grid fade-in">
  <div class="rg-item lift">
    <h3>🔥 Chemical Looping</h3>
    <p>Advancing chemical looping technologies for low-carbon hydrogen production, CO₂ capture, syngas generation, and industrial decarbonisation.</p>
  </div>

  <div class="rg-item lift">
    <h3>🧪 Functional Materials</h3>
    <p>Design and deployment of oxygen carriers, catalysts, and sorbents, including Ca/Mn co-doped LaNiO3 and industrial Ca-, Cu-, Ni-, and Fe-based materials for high-temperature conversion processes.</p>
  </div>

  <div class="rg-item lift">
    <h3>⚙️ Process Modelling & Digitalisation</h3>
    <p>Multi-scale modelling using gPROMS, CFD, Aspen Plus®, and machine learning approaches to accelerate process understanding, optimisation, and scale-up.</p>
  </div>

  <div class="rg-item lift">
    <h3>🌱 CO₂ Utilisation & Net-Zero Pathways</h3>
    <p>CL-RWGS-based syngas production, sustainable fuel pathways, and integrated techno-economic (TEA) and life-cycle (LCA) assessments for industrial decarbonisation.</p>
  </div>
</div>

---

<div class="home-cards">

  <div>
    <h3><a href="/people/">👥 People</a></h3>
    <p>Meet the researchers driving innovation in thermochemical engineering.</p>
  </div>

  <div>
    <h3><a href="/publications/">📄 Publications</a></h3>
    <p>Explore our journal articles, conference papers, theses, and preprints.</p>
  </div>

  <div>
    <h3><a href="/contact/">✉️ Contact</a></h3>
    <p>For collaborations or enquiries, reach out via email or visit our laboratory.</p>
  </div>

</div>

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
