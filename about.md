<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="alternate" type="application/rss+xml" title="Chemobrionics Database" href="https://cpimentelguerra.com/new-chemDB/feed.xml" />

<div id="menu-placeholder"></div>
<script>
  fetch('menu.html')
    .then(response => response.text())
    .then(data => {
      document.getElementById('menu-placeholder').innerHTML = data;
    });
</script>
</head>

<body>
## About us

The work team of the Chemobrionics Database is:

* Carlos Pimentel

* Mingchuan Zheng

* C. Ignacio Sainz-Díaz

* Julyan H. E. Cartwright

<BR>

*Acknowledgements*

The authors would like to acknowledge the contribution of the European COST Action CA17120 supported by the EUFramework Programme Horizon 2020.

Carlos Pimentel has received funding from the European Union Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement No. 101021894 [CARS-CO2]. (From February 2022 to January 2024)

</body>
</html>

