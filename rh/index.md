---
title: Research Highligts
layout: default
---

<h1><strong>Join a community of passionate researchers<br>pushing the boundaries of soil macroecology</strong></h1>
<p>At Blackbox, you'll collaborate on groundbreaking projects, access cutting-edge resources, and contribute to research with global impact. Whether you're a student eager to make your mark or an established researcher looking to expand your horizons, Blackbox offers the opportunity to grow, innovate, and lead in this field.</p>
<a href="/blackbox.github.io/people">
    <img src="/blackbox.github.io/assets/images/img/people_v2.svg" alt="People">
</a>
<a href="/blackbox.github.io/fp">
    <img src="/blackbox.github.io/assets/images/img/feat_proj.svg" alt="Featured Projects">
</a>
</div>
    <h2><strong>Collaborations across the world</strong></h2>
        <!-- Add a container div with a class for better control -->
    <div class="map-container">
            <!-- The map div where Leaflet will render the map -->
        <div id="map" style="height: 500px;"></div>
    </div>
        <!-- Leaflet CSS and JS -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
    <script>
            // Initialize the map centered in the middle of the Atlantic Ocean with a zoomed-out view
        var map = L.map('map').setView([14.5994, -28.6731], 3); // Coordinates in the middle of the Atlantic with a low zoom level (3)
            // Add OpenStreetMap tiles to the map
        L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
        }).addTo(map);
            // Load GeoJSON data from an external file
        fetch('assets/your-geojson-file.geojson')
            .then(response => response.json())
            .then(data => {
                L.geoJSON(data).addTo(map);
        });
            // Add markers and popups
            var marker1 = L.marker([40.21119, -8.42946]).addTo(map);
            marker1.bindPopup("<b>Homebase</b><br>Universidade de Coimbra").openPopup();
            var marker2 = L.marker([38.56667, -7.9]).addTo(map);
            marker2.bindPopup("<b>Teresa Pinto Correia</b><br>Universidade de Évora").openPopup();
            var marker3 = L.marker([37.38283, -5.97317]).addTo(map);
            marker3.bindPopup("<b>Manuel Delgado-Baquerizo</b><br>Instituto de Recursos Naturales y Agrobiología de Sevilla").openPopup();
            var marker4 = L.marker([24.266906, 45.107849]).addTo(map);
            marker4.bindPopup("<b>Fernando Maestre</b><br>King Abdullah University of Science and Technology").openPopup();
            var marker5 = L.marker([58.38062, 26.72509]).addTo(map);
            marker5.bindPopup("<b>Leho Tedersoo</b><br>Tartu University").openPopup();
            var marker6 = L.marker([41.55032, -8.42005]).addTo(map);
            marker6.bindPopup("<b>Sofia Costa</b><br>University of Minho").openPopup();
            var marker7 = L.marker([41.69323, -8.83287]).addTo(map);
            marker7.bindPopup("<b>Susana Mendes</b><br>Polytechnic Institute of Viana do Castelo").openPopup();
            var marker8 = L.marker([51.33962, 12.37129]).addTo(map);
            marker8.bindPopup("<b>Nico Eisenhauer</b><br>German Center for Integrative Biodiversity Research").openPopup();
            var marker9 = L.marker([41.38879, 2.15899]).addTo(map);
            marker9.bindPopup("<b>Salvador Lladó</b><br>University of Barcelona").openPopup();
            var marker10 = L.marker([45.8148, 8.61294]).addTo(map);
            marker10.bindPopup("<b>Arwyn Jones</b><br>Joint Research Center").openPopup();
            var marker11 = L.marker([51.97, 5.66667]).addTo(map);
            marker11.bindPopup("<b>Wim van der Putten</b><br>Nederlands Instituut voor Ecologie").openPopup();
            var marker12 = L.marker([-33.8559799094, 151.20666584]).addTo(map);
            marker12.bindPopup("<b>Brajesh K. Singh</b><br>Western Sydney University").openPopup();
            var marker13 = L.marker([41.35481, -8.7434]).addTo(map);
            marker13.bindPopup("<b>Angela Lomba</b><br>Centro de Investigação em Biodiversidade e Recursos Genéticos").openPopup();
            var marker14 = L.marker([-31.4135, -64.18105]).addTo(map);
            marker14.bindPopup("<b>Pedro Jaureguiberry</b><br>Instituto Multidisciplinario de Biología Vegetal").openPopup();
            var marker15 = L.marker([38.71667, -9.13333]).addTo(map);
            marker15.bindPopup("<b>Maria São Luis Centeno</b><br>Direção-Geral de Agricultura e Desenvolvimento Rural").openPopup();
            var marker16 = L.marker([-23.5475, -46.63611]).addTo(map);
            marker16.bindPopup("<b>George Brown</b><br>Brazilian Agricultural Research Corporation").openPopup();
            var marker17 = L.marker([-34.90328, -56.18816]).addTo(map);
            marker17.bindPopup("<b>María Revetria</b><br>Soil Microbiology Laboratory").openPopup();
        </script>
        
## **Publications**
- **2024**
  - {% include publications year="2024" %}
- **2023**
  - {% include publications year="2023" %}
- **2022**
  - {% include publications year="2022" %}
- **2021**
  - {% include publications year="2021" %}
- **2020**
  - {% include publications year="2020" %}
- **2019**
  - {% include publications year="2019" %}
- **2018**
  - {% include publications year="2018" %}
- **2017**
  - {% include publications year="2017" %}
- **2016**
  - {% include publications year="2016" %}
- **2015**
  - {% include publications year="2015" %}
### **Before 2015**
- {% include publications year="2014;2013;2012;2011;2007;2004" %}
