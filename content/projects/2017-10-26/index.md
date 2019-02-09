<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
  padding: 20px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- MAIN (Center website) -->
<div class="main">

<h1>i dont have money to buy my paint</h1>
<hr>

<h2>ANTIPORTFOLIO</h2>
<p>h e l p.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="/w3images/pilt12.jpg" alt="Mountains" style="width:100%">
      <h3>need</h3>
      <p>..............</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="/pilt13.jpg" alt="Lights" style="width:100%">
      <h3>wish</h3>
      <p>...............</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="/pilt14" alt="Nature" style="width:100%">
      <h3>.............</h3>
      <p>...............</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="/pilt15.jpg" alt="Mountains" style="width:100%">
      <h3>want</h3>
      <p>.................</p>
    </div>
  </div>
<!-- END GRID -->
</div>

<div class="content">
  <img src="/pilt16.jpg" alt="Bear" style="width:100%">
  <h3>still here</h3>
  <p>...............</p>
  <p>...............</p>
</div>

<!-- END MAIN -->
</div>

</body>
</html>















 


