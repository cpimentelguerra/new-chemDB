<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {margin:0;font-family:Arial}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.active {
  background-color: royalblue;
  color: white;
}

.topnav .icon {
  display: none;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 17px;    
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.topnav a:hover, .dropdown:hover .dropbtn {
  background-color: #555;
  color: white;
}

.dropdown-content a:hover {
  background-color: #ddd;
  color: black;
}

.dropdown:hover .dropdown-content {
  display: block;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child), .dropdown .dropbtn {
    display: none;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
  .topnav.responsive .dropdown {float: none;}
  .topnav.responsive .dropdown-content {position: relative;}
  .topnav.responsive .dropdown .dropbtn {
    display: block;
    width: 100%;
    text-align: left;
  }
}
</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a class="active" href="https://cpimentelguerra.com/new-chemDB/">Home</a>
  <a href="https://cpimentelguerra.com/new-chemDB/zotero">Zotero library</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtouse">How to use</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtocite">How to cite</a>
  <a href="https://cpimentelguerra.com/new-chemDB/about">About us</a>
  <a href="https://cpimentelguerra.com/#contact">Contact</a>
  <a href="https://cpimentelguerra.com/new-chemDB/updates">Updates</a>
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
</script>

</body>
</html>

<br>

The Chemobrionics Database is a database which aims to curate all the scientific works performed about chemobrionics. In this database, previously reported chemical gardens are classified using the anions and cations used, and the setup in which the chemical garden growth were promoted. In all cases, the last column is devoted to provide the references where such experiments were described. All these references are also curated in a [Zotero group library](/chemicalgardens/zotero)

If you find this database useful and you use it in your work, please [cite](/chemicalgardens/howtocite) it as follows:

* Pimentel, Carlos, Zheng, Mingchuan, Cartwright, Julyan H. E., & Sainz-Díaz, C. Ignacio  (2023). Chemobrionics Database: Categorisation of Chemical Gardens According to the Nature of the Anion, Cation and Experimental Procedure. *ChemSystemsChem*, 5, e202300002. DOI: [10.1002/syst.202300002](https://doi.org/10.1002/syst.202300002)

* Pimentel, Carlos, Zheng, Mingchuan, Sainz-Díaz, C. Ignacio, & Cartwright, Julyan H. E. (2022). Chemobrionics Database (0.0.19) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.10911844

In addition, if you miss your work in the database, please let us know to update it (cpimentelguerra@geo.ucm.es).

<html>
  <body> 
    <iframe style="border-style: none;" src="https://cpimentelguerra.com/chemobrionics/database/database.html" width="100%" height="600" id="Iframe"></iframe>

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
