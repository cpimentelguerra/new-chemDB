<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="alternate" type="application/rss+xml" title="Chemobrionics Database" href="https://cpimentelguerra.com/new-chemDB/feed.xml" />
  
<div class="topnav" id="myTopnav">
  <a href="https://cpimentelguerra.com/new-chemDB/" class="menu-link">Home</a>
  <a href="https://cpimentelguerra.com/new-chemDB/zotero" class="menu-link">Zotero library</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtouse" class="menu-link">How to use</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtocite" class="menu-link">How to cite</a>
  <a href="https://cpimentelguerra.com/new-chemDB/about" class="menu-link">About us</a>
  <a href="https://cpimentelguerra.com/#contact" class="menu-link">Contact</a>
  <a href="https://cpimentelguerra.com/new-chemDB/updates" class="menu-link">Updates</a>
  <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
</div>

<script>
  function myFunction() {
    var x = document.getElementById("myTopnav");
    if (x.className === "topnav") {
      x.className += " responsive";
    } else {
      x.className = "topnav";
    }
  }

  // Esperar a que el DOM esté completamente cargado
  document.addEventListener("DOMContentLoaded", function() {
    // Obtener la URL actual
    const currentURL = window.location.href;

    // Seleccionar todos los enlaces del menú
    const links = document.querySelectorAll('.menu-link');

    // Comparar la URL de cada enlace con la URL actual
    links.forEach(link => {
      if (link.href === currentURL) {
        link.classList.add('active'); // Agregar la clase 'active' al enlace actual
      }
    });
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

