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


<br>

<p>The Chemobrionics Database is a database which aims to curate all the scientific works performed about chemobrionics. In this database, previously reported chemical gardens are classified using the anions and cations used, and the setup in which the chemical garden growth were promoted. In all cases, the last column is devoted to provide the references where such experiments were described. All these references are also curated in a <a href="/new-chemDB/zotero">Zotero group library</a></p>

If you find this database useful and you use it in your work, please [cite](/new-chemDB/howtocite) it as follows:

* Pimentel, Carlos, Zheng, Mingchuan, Cartwright, Julyan H. E., & Sainz-Díaz, C. Ignacio  (2023). Chemobrionics Database: Categorisation of Chemical Gardens According to the Nature of the Anion, Cation and Experimental Procedure. *ChemSystemsChem*, 5, e202300002. DOI: [10.1002/syst.202300002](https://doi.org/10.1002/syst.202300002)

* Pimentel, Carlos, Zheng, Mingchuan, Sainz-Díaz, C. Ignacio, & Cartwright, Julyan H. E. (2022). Chemobrionics Database (0.0.19) [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.10911844](https://doi.org/10.5281/zenodo.10911844)

In addition, if you miss your work in the database, please let us know to update it (cpimentelguerra@geo.ucm.es).

</body>

<html>
  <body> 
    <iframe style="border-style: none;" src="https://cpimentelguerra.com/chemobrionics/database/database.html" width="100%" height="1000" id="Iframe"></iframe>

    <script> 
        // Selecting the iframe element 
        var frame = document.getElementById("Iframe"); 
          
        // Adjusting the iframe height onload event 
        frame.onload = function() 
        // function execute while load the iframe 
        { 
          // set the height of the iframe as  
          // the height of the iframe content 
          frame.style.height =  
          frame.contentWindow.document.body.scrollHeight + 'px'; 
           
  
         // set the width of the iframe as the  
         // width of the iframe content 
         frame.style.width  =  
          frame.contentWindow.document.body.scrollWidth+'px'; 
              
        } 
    </script> 
  </body>  
</html>
