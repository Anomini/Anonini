<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>אתר לקבלת עוקבים חינם</title>
<style>
h1 {
font-size: 70px;
text-align: center;
}
button {
background-color: blue;
color: white;
font-size: 56px;
display: block;
margin: 110px auto;
}
img {
display: block;
margin: 20px auto;
}
</style>
<script>
function openOptions() {
var choice = prompt("בחר את מספר העוקבים שברצונך לקבל (100, 500, 1000):");
if (choice === "100" || choice === "500" || choice === "1000") {
alert("בחרת ב-" + choice + " עוקבים");
document.getElementById("selectedFollowers").innerHTML = choice + " עוקבים";
document.getElementById("getFollowersBtn").disabled = false;
} else {
alert("אנא בחר רק 100 או 500 או 1000 עוקבים");
}
}
</script>
</head>
<body>
<h1>אתר לקבלת עוקבים באינסטגרם בחינם</h1>
<img src="1.jpg" alt="תמונה 1" style="display: block; margin: 20px auto;width: 50%;">
<button onclick="openOptions()">בחר מספר עוקבים</button>
<div id="selectedFollowers" style="text-align: center;"></div>
<button id="getFollowersBtn" style="margin-top: 20px;" onclick="window.location.href='2.html';" disabled>קבל את העוקבים שלך</button>
</body>
</html>
