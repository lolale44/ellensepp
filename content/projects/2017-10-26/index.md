<!-- MAIN (Center website) -->
<div class="main">

<h1>h e l p</h1>
<hr>

<h2>ANTIPORTFOLIO</h2>
<p>i don't have money to buy my paint.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="pilt11.jpg" alt="Mountains" style="width:100%">
      <h3>wish</h3>
      <p>.........</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="pilt14.jpg" alt="Lights" style="width:100%">
      <h3>want</h3>
      <p>...........</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="pilt13.jpg" alt="Nature" style="width:100%">
      <h3>need</h3>
      <p>............</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="pilt15.jpg" alt="Mountains" style="width:100%">
      <h3>here</h3>
      <p>.............</p>
    </div>
  </div>
</div>

<div class="content">
  <img src="pilt12.jpg" alt="Bear" style="width:100%">
  <h3>still</h3>
  <p>................</p>
</div>

<!-- END MAIN -->
</div>


 {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
  padding: 20px;
  font-family: Arial;
}


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


.row,
.row > .column {
  padding: 8px;
}


.column {
  float: left;
  width: 25%;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}


.content {
  background-color: white;
  padding: 10px;
}


@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}


@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}



