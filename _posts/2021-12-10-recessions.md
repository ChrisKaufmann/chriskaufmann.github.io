---
title: "Recessions by birth year"
date: 2021-12-10
permalink: /recessions-by-birth-year
webrick:
  headers:
    Access-Control-Allow-Origin: "*"
---
<div>
<p>
This kind of thing is actually fascinating to read about. Since the great depression, there have been recessions in: '45, '49, '53, '57, '60, '70, '73, '80, '90, '01, '08, and '20. There is literally no time in the last 80+ years where a 35 year old wouldn't have lived through at least three economic contractions. Though the most recent two are the worst since the great depression, with the longest expansion (measured by job growth) since said great depression in between (the longest before that being the Clinton years of the 90's). I guess what I'm saying is yeah it sucks for Millenials but primarily because of the severity of the last two, not the number of them.<br>
<p>
If you count working ages (let's go with the coveted 18-34 demographic, for fun), it's a little more interesting-<br>
1939 has 4<br>
63-66, 73, and 84-85 only have one<br>
40-42, 46-52 have three<br>
The rest: 44-45, 53-62,73, and 86-87 (having the two big ones) have two.<br>
(A note on the data, it is only counting the start year of the recessions, and not multiple-year long ones just because the math is easier. This affects 73-75, 80-82, 90-91, and 08-09 and mostly makes those born from 46-62 have drastically more, at least 5 and as high as 7. Amazingly, the 2020 recession only officially lasted two months but was so drastic that it still reverberates)
</p>
</div>
<div id="line_chart" style="width: 900px; height: 500px"></div>
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script>
  google.charts.load('current', {packages: ['line']});
  google.charts.setOnLoadCallback(drawChart);

  function drawChart() {
  var data = new google.visualization.DataTable();
  data.addColumn('date', 'Year');
  data.addColumn('number', '0-34');
  data.addColumn('number', '18-34');
  data.addColumn('number', '18-34**');
  data.addRows([
  [new Date(1939,0,0),7,4,4],
  [new Date(1940,0,0),7,3,4],
  [new Date(1941,0,0),7,3,5],
  [new Date(1942,0,0),7,3,5],
  [new Date(1943,0,0),7,2,4],
  [new Date(1944,0,0),7,2,4],
  [new Date(1945,0,0),7,2,4],
  [new Date(1946,0,0),7,3,5],
  [new Date(1947,0,0),7,3,6],
  [new Date(1948,0,0),7,3,7],
  [new Date(1949,0,0),7,3,7],
  [new Date(1950,0,0),6,3,7],
  [new Date(1951,0,0),6,3,7],
  [new Date(1952,0,0),6,3,7],
  [new Date(1953,0,0),6,2,6],
  [new Date(1954,0,0),5,2,6],
  [new Date(1955,0,0),5,2,6],
  [new Date(1956,0,0),6,2,6],
  [new Date(1957,0,0),6,2,6],
  [new Date(1958,0,0),5,2,5],
  [new Date(1959,0,0),5,2,5],
  [new Date(1960,0,0),5,2,5],
  [new Date(1961,0,0),4,2,5],
  [new Date(1962,0,0),4,2,5],
  [new Date(1963,0,0),4,1,4],
  [new Date(1964,0,0),4,1,3],
  [new Date(1965,0,0),4,1,2],
  [new Date(1966,0,0),4,1,2],
  [new Date(1967,0,0),5,2,3],
  [new Date(1968,0,0),5,2,3],
  [new Date(1969,0,0),5,2,3],
  [new Date(1970,0,0),5,2,3],
  [new Date(1971,0,0),4,2,3],
  [new Date(1972,0,0),4,2,3],
  [new Date(1973,0,0),4,1,2],
  [new Date(1974,0,0),4,2,2],
  [new Date(1975,0,0),4,2,3],
  [new Date(1976,0,0),4,2,3],
  [new Date(1977,0,0),4,2,3],
  [new Date(1978,0,0),4,2,3],
  [new Date(1979,0,0),4,2,3],
  [new Date(1980,0,0),4,2,3],
  [new Date(1981,0,0),3,2,3],
  [new Date(1982,0,0),3,2,3],
  [new Date(1983,0,0),3,2,3],
  [new Date(1984,0,0),3,1,2],
  [new Date(1985,0,0),3,1,2],
  [new Date(1986,0,0),4,2,3],
  [new Date(1987,0,0),4,2,3]
 ]);
  var options = {
    hAxis: {
      format: 'yyyy'
	},
    chart: {
	  title: 'Recessions by year of birth before age of 35',
	  subtitle: '** denotes mult-year recessions'
	}
  }
  var chart = new google.charts.Line(document.getElementById('line_chart'));
  chart.draw(data, google.charts.Line.convertOptions(options));
}
</script>

