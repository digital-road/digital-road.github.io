<template>
<div>
  <h3>My Google Maps Demo</h3>
    <!--The div element for the map -->
    <div id="map"></div>
</div>
</template>
<script>
var map;
      function initMap() {
        map = new google.maps.Map(document.getElementById('map'), {
          center: {lat: -34.397, lng: 150.644},
          zoom: 8
        });
      }
</script>
<style>
#map {
        height: 100%;
}
/* Optional: Makes the sample page fill the window. */
html, body {
        height: 100%;
        margin: 0;
        padding: 0;
}
</style>
