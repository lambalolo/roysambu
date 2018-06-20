<!DOCTYPE html>
<html>
<head>
<script src="http://maps.googleapis.com/maps/api/js"></script>
<script>
function loadMap() {
var mapOptions = {
center:new google.maps.LatLng(-1.218459, 36.886906),
zoom:17,
mapTypeId:google.maps.MapTypeId.TERRAIN
};
var map=new google.maps.Map(document.getElementById("sample"),mapOptions);
var marker = new google.maps.Marker({
position: new google.maps.LatLng(-1.218459, 36.886906),
map: map,
});
}
</script>
</head>
<body onload="loadMap()">
<div id="sample" style="width:1200px;height:600px;"></div>
</body>
</html>
