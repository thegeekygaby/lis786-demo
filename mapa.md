---
title: Mapa
layout: default
permalink: /mapa/
---
# Mapa

{% include wip.html %}

Esta pagina tendra un mapa donde podra ver las organizaciones en su area.

<iframe width="600" height="450" frameborder="0" style="border:0"
src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJnwYzXbSzD4gR3738fwb3ql0&key=AIzaSyCi-yz2py5r6VlVoFjnenizfSv_1iPU3JE" allowfullscreen></iframe>

<script>
// Initialize and add the map
function initMap() {
// The location of Uluru
var uluru = {lat: -25.344, lng: 131.036};
// The map, centered at Uluru
var map = new google.maps.Map(
    document.getElementById('map'), {zoom: 4, center: uluru});
// The marker, positioned at Uluru
var marker = new google.maps.Marker({position: uluru, map: map});
}
  </script>
  <script async defer
  src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
  </script>

*This page will soon hold a map to highlight relevant organizations.*
