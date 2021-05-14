<html>
	<body>        		
		
 <h1>30 Random Developing Countries</h1>
		<p id="demo">Generate.</p>
    <script>
document.getElementById("demo").onclick = function() {myFunction()};
function myFunction() {
  
var words = ["Maldives",
"Tunisia",
"Saint Vincent and the Grenadines",
"Suriname",
"Mongolia",
"Botswana",
"Jamaica",
"Jordan",
"Paraguay",
"Tonga",
"Libya",
"Uzbekistan",
"Bolivia (Plurinational State of)",
"Indonesia",
"Philippines",
"Belize",
"Samoa",
"Turkmenistan",
"Venezuela (Bolivarian Republic of)",
"South Africa",
"Palestine, State of",
"Egypt",
"Marshall Islands",
"Vietnam",
"Gabon",
"Kyrgyzstan",
"Morocco",
"Guyana",
"Iraq",
"El Salvador",
"Tajikistan",
"Guatemala",
"Nicaragua",
"Bhutan",
"Namibia",
"India",
"Honduras",
"Bangladesh",
"Kiribati",
"Sao Tome and Principe",
"Micronesia (Federated States of)",
"Lao People's Democratic Republic",
"Eswatini (Kingdom of)",
"Ghana",
"Vanuatu",
"Timor-Leste",
"Nepal",
"Kenya",
"Cambodia",
"Equatorial Guinea",
"Zambia",
"Myanmar",
"Angola",
"Congo",
"Zimbabwe",
"Solomon Islands",
"Syrian Arab Republic",
"Cameroon",
"Pakistan",
"Papua New Guinea",
"Comoros",
"Mauritania",
"Benin",
"Uganda",
"Rwanda",
"Nigeria",
"Côte d'Ivoire",
"Tanzania (United Republic of)",
"Madagascar",
"Lesotho",
"Djibouti",
"Togo",
"Senegal",
"Afghanistan",
"Haiti",
"Sudan",
"Gambia",
"Ethiopia",
"Malawi",
"Congo (Democratic Republic of the)",
"Guinea-Bissau",
"Liberia",
"Guinea",
"Yemen",
"Eritrea",
"Mozambique",
"Burkina Faso",
"Sierra Leone",
"Mali",
"Burundi",
"South Sudan",
"Chad",
"Central African Republic",
"Niger"];

function fisherYates (arr) {
  for (var i = arr.length - 1; i >= 0; i--) {
    var j = Math.floor(Math.random() * (i + 1));
    var temp = arr[i];
    arr[i] = arr[j];
    arr[j] = temp;
  }
  return arr;
}

f=fisherYates(words);

document.getElementById("demo").innerHTML = ("<p>" + f[0] + "</p>" + "<p>" + f[1] + "</p>" + "<p>" + f[2] + "</p>" + "<p>" + f[3] + "</p>" + "<p>" + f[4] + "</p>" + "<p>" + f[5] + "</p>" + "<p>" + f[6] + "</p>" + "<p>" + f[7] + "</p>" + "<p>" + f[8] + "</p>" + "<p>" + f[9] + "</p>" + "<p>" + "<p>" + f[10] + "</p>" + "<p>"+ "<p>" + f[11] + "</p>" + "<p>"+ "<p>" + f[12] + "</p>" + "<p>"+ "<p>" + f[13] + "</p>" + "<p>"+ "<p>" + f[14] + "</p>" + "<p>"+ "<p>" + f[15] + "</p>" + "<p>"+ "<p>" + f[16] + "</p>" + "<p>"+ "<p>" + f[17] + "</p>" + "<p>"+ "<p>" + f[18] + "</p>" + "<p>"+ "<p>" + f[19] + "</p>" + "<p>"+ "<p>" + f[20] + "</p>" + "<p>"+ "<p>" + f[21] + "</p>" + "<p>"+ "<p>" + f[22] + "</p>" + "<p>"+ "<p>" + f[23] + "</p>" + "<p>"+ "<p>" + f[24] + "</p>" + "<p>"+ "<p>" + f[25] + "</p>" + "<p>"+ "<p>" + f[26] + "</p>" + "<p>"+ "<p>" + f[27] + "</p>" + "<p>"+ "<p>" + f[28] + "</p>" + "<p>"+ "<p>" + f[29] + "</p>" + "<p>");}
    </script>
    
<FORM>
<INPUT Type="button" VALUE="Reload Page" onClick="history.go(0)">
</FORM>
    <body>   

