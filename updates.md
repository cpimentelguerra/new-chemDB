---
title: Posts
---

<ul class="posts">
  {% for post in site.categories.posts %}
    <li class="post">
      <a href="{{ post.url }}">{{ post.title }}</a>
      <time class="publish-date" datetime="{{ post.date | date: '%F' }}">
        {{ post.date | date: "%B %-d, %Y" }}
      </time>
    </li>
  {% endfor %}
</ul>

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
  <a href="https://cpimentelguerra.com/new-chemDB/">Home</a>
  <a href="https://cpimentelguerra.com/new-chemDB/zotero">Zotero library</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtouse">How to use</a>
  <a href="https://cpimentelguerra.com/new-chemDB/howtocite">How to cite</a>
  <a href="https://cpimentelguerra.com/new-chemDB/about">About us</a>
  <a href="https://cpimentelguerra.com/#contact">Contact</a>
  <a class="active" href="https://cpimentelguerra.com/new-chemDB/updates">Updates</a>
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



## New version alpha-0.0.19b
###### Last updated on May 21, 2024

A new version of the database has been published. It includes the following papers:

* Knoll P. and Loron C. C. (2024) Effect of Temperature on Calcium-based Chemical Garden Growth. ChemSystemsChem. [https://doi.org/10.1002/syst.202400012](https://doi.org/10.1002/syst.202400012)

* Testón-Martínez S., Barge L. M., Eichler J., Sainz-Díaz C. I. and Cartwright J. H. E. (2024) Experimental modelling of the growth of tubular ice brinicles from brine flows under sea ice. The Cryosphere 18, 2195–2205. [https://doi.org/10.5194/tc-18-2195-2024](https://doi.org/10.5194/tc-18-2195-2024)

This is a minor update and the database has not been updated in Zenodo.
