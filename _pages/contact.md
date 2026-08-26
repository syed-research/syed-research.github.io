---
title: "Contact"
layout: single
permalink: /contact/
toc: false
---

If you’d like to get in touch with the CLIMATE Research Group or discuss collaboration opportunities, please use the details below.

---

## 📍 Location

<div style="display:flex; gap:20px; align-items:flex-start; flex-wrap:wrap; margin-top:15px;">

  <!-- Left column: location text -->
  <div style="flex:1; min-width:260px;">
    <p>
      School of Chemistry and Chemical Engineering<br>
      University of Southampton<br>
      Southampton, United Kingdom
    </p>
  </div>

  <!-- Right column: custom pin map -->
  <div style="flex:1; min-width:260px;">
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

    <div id="climate-map" style="width:100%; height:250px; border-radius:8px; margin-top:10px;"></div>

    <script>
      // Create map
      var map = L.map('climate-map').setView([50.9351, -1.3985], 15);

      // Add tile layer
      L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        maxZoom: 19,
        attribution: '© OpenStreetMap'
      }).addTo(map);

      // Custom CLIMATE pin
      var customIcon = L.icon({
        iconUrl: '/assets/images/map-pin.svg',
        iconSize: [48, 48],
        iconAnchor: [24, 48]
      });

      // Add marker
      L.marker([50.9351, -1.3985], { icon: customIcon })
        .addTo(map)
        .bindPopup("<b>University of Southampton</b><br>School of Chemistry & Chemical Engineering");
    </script>
  </div>

</div>


---

## 📧 Email

For research enquiries, supervision requests, or collaboration discussions:

**s.z.abbas@soton.ac.uk**

---

## 🧑‍🏫 Academic Profiles

- [Google Scholar](https://scholar.google.com/citations?user=UmP3K1cAAAAJ&hl=en)  
- [University Profile](https://www.southampton.ac.uk/people/62bw6h/doctor-syed-zaheer-abbas)  
- [ORCID](https://orcid.org/0000-0002-8783-8572)  
- [ResearchGate](https://www.researchgate.net/)  
- [LinkedIn](https://www.linkedin.com/in/syed-zaheer-abbas-387609148/)  

---

## 🧪 Research Areas

- Chemical Looping  
- Ca–Cu Looping  
- Hydrogen Production  
- CO₂ Utilisation  
- CO₂ Capture  
- Reactor Modelling  
- Industrial Decarbonisation  

---

## 🏢 Collaboration & Industry

We welcome collaboration with:

- Industrial partners  
- Academic institutions  
- Research centres  
- Government and policy groups  

If you’re interested in working with us, please reach out via email.

---

## 📝 General Enquiries

For general questions about the CLIMATE Research Group:

**s.z.abbas@soton.ac.uk**
