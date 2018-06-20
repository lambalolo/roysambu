<!DOCTYPE html>
<html>
<head>
<title>ROYSA</title>
<style>
	    *{
		   margin: 0;
		   padding: 0;
		}
	    #map {
	       height: 500px;
		   width: 100%;
		}
</style>	
</head>
<body>

<div id="map">
</div>
<script>
	function initMap() {
		var location = {lat:-1.218459 , lng:36.886906}
		var map = new google.maps.Map(document.getElementById("map"), {
			zoom: 4,
			center: location 
			});
		var marker = new gogle.maps.Marker({
			position: location,
			map: map			
		});		
	}
</script>
<script async defer src="https://maps.googleapis.com/maps/api/
js?key=AIzaSyAsfdiHHtiHZde-UFbxZBiVO064E-1WY04 ></script>
</body>
</html>
	
