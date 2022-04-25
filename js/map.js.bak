var map;
function initMap() {
  map = new google.maps.Map(document.getElementById('map'), {
    center: {lat: 41.835471, lng: -87.625888},
    zoom: 16
  });

  var marker = new google.maps.Marker({
		position: new google.maps.LatLng(41.835471, -87.625888),
		map: map, 
    icon: './assets/images/mtcc.jpg'
  });

  var infowindow = new google.maps.InfoWindow({
    content: "<h1>IIT MTCC</h1><p>IIT mostly resolves around the MTCC. It's where most students go to eat their lunch and dinner. There is also a 7 .<p>"
  });

  google.maps.event.addListener(marker, 'mouseover', function() {
    infowindow.open(map, marker);
  });

  var marker2 = new google.maps.Marker({
		position: new google.maps.LatLng(41.837857591216, -87.62491299248141),
		map: map, 
    icon: './assets/images/kacek.jpg'
  });

  var infowindow2 = new google.maps.InfoWindow({
    content: "<h1>Kacek Building</h1><p>Kacek is my dorm room and is also a the home of many college students like me.<p>"
  });

  google.maps.event.addListener(marker2, 'mouseover', function() {
    infowindow2.open(map, marker2);
  });
}
google.maps.event.addDomListener(window, 'load', initMap);