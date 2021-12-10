---
title: "Recessions by birth year"
date: 2021-12-10
permalink: /recessions-by-birth-year
webrick:
  headers:
    Access-Control-Allow-Origin: "*"
---
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script>
google.charts.load('current', {packages: ['corechart', 'line']});
google.charts.setOnLoadCallback(drawAxisTickColors);
function drawChart() {
 var data = google.visualization.arrayToDataTable([
  ['Year','0-34','18-34','18-34*'],
  ["1939",7,4,4],
  ["1940",7,3,4],
  ["1941",7,3,5],
  ["1942",7,3,5],
  ["1943",7,2,4],
  ["1944",7,2,4],
  ["1945",7,2,4],
  ["1946",7,3,5],
  ["1947",7,3,6],
  ["1948",7,3,7],
  ["1949",7,3,7],
  ["1950",6,3,7],
  ["1951",6,3,7],
  ["1952",6,3,7],
  ["1953",6,2,6],
  ["1954",5,2,6],
  ["1955",5,2,6],
  ["1956",6,2,6],
  ["1957",6,2,6],
  ["1958",5,2,5],
  ["1959",5,2,5],
  ["1960",5,2,5],
  ["1961",4,2,5],
  ["1962",4,2,5],
  ["1963",4,1,4],
  ["1964",4,1,3],
  ["1965",4,1,2],
  ["1966",4,1,2],
  ["1967",5,2,3],
  ["1968",5,2,3],
  ["1969",5,2,3],
  ["1970",5,2,3],
  ["1971",4,2,3],
  ["1972",4,2,3],
  ["1973",4,1,2],
  ["1974",4,2,2],
  ["1975",4,2,3],
  ["1976",4,2,3],
  ["1977",4,2,3],
  ["1978",4,2,3],
  ["1979",4,2,3],
  ["1980",4,2,3],
  ["1981",3,2,3],
  ["1982",3,2,3],
  ["1983",3,2,3],
  ["1984",3,1,2],
  ["1985",3,1,2],
  ["1986",4,2,3],
  ["1987",4,2,3]
 ]);
}
var options = {
  title: 'Recessions by year of birth before age of 35',
  legend: {position: 'bottom'}
}
  var chart = new google.visualization.LineChart(document.getElementById('line_chart'));
  chart.draw(data, options);
</script>

<div id="line_chart" style="width: 900px; height: 500px"></div>
