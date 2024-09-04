---
layout: default
---

# **Join a community of passionate researchers pushing the boundaries of soil science**

At Blackbox, you'll collaborate on groundbreaking projects, access cutting-edge resources, and contribute to research with global impact. Whether you're a student eager to make your mark or an established researcher looking to expand your horizons, Blackbox offers the opportunity to grow, innovate, and lead in this field.


## **Colaborations across the world**

<div id="map" style="height: 500px;"></div>

<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />

<script>
  // Initialize the map centered on a specific location
  var map = L.map('map').setView([37.7749, -122.4194], 10); // Example: San Francisco coordinates

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

  // Add a marker to the map at a specific location
  var marker = L.marker([37.7749, -122.4194]).addTo(map); // Example: San Francisco coordinates

  // Optional: Add a popup to the marker
  marker.bindPopup("<b>Carlos!</b><br>https://en.wikipedia.org/wiki/San_Francisco").openPopup();

  var marker = L.marker([39.557191, -7.8536599]).addTo(map); // Example: Portugal coordinates

  // Optional: Add a popup to the marker
  marker.bindPopup("<b>Portugal!</b><br>https://en.wikipedia.org/wiki/Portugal").openPopup();

  var marker = L.marker([40.21119, -8.42946]).addTo(map); // Example: Coimbra coordinates

  // Optional: Add a popup to the marker
  marker.bindPopup("<b>Coimbra!</b><br>Im lazy to write.").openPopup();
</script>



## **Publications**

*2024*

{% include publications year="2024" %}

*2023*

{% include publications year="2023" %}

*2022*

{% include publications year="2022" %}

*2021*

{% include publications year="2021" %}

*2020*

{% include publications year="2020" %}

*2019*

{% include publications year="2019" %}

*2018*

{% include publications year="2018" %}

*2017*

{% include publications year="2017" %}

*2016*

{% include publications year="2016" %}

*2015*

{% include publications year="2015" %}

#### **Before 2015**

{% include publications year="2014;2013;2012;2011;2007;2004" %}

<br>
<br>