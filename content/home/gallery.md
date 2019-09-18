+++

# About widget.
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear in.

title = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
  
+++

<!DOCTYPE html>
<html>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}
{
/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}
</style>
<body>

<!-- Header -->
<div class="header">
  <h1>Responsive Image Grid</h1>
  <p>Resize the browser window to see the responsive effect.</p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="img/dog_1.jpg" style="width:100%">
    <img src="img/dog_2.jpg" style="width:100%">
    <img src="img/dog_3.jpg" style="width:100%">
    <img src="img/dog_4.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="img/dog_5.jpg" style="width:100%">
    <img src="img/dog_6.jpg" style="width:100%">
  </div>  
  <div class="column">
    <img src="img/dog_7.jpg" style="width:100%">
    <img src="img/dog_8.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="img/dog_9.jpg" style="width:100%">
    <img src="img/dog_10.jpg" style="width:100%">
  </div>
</div>

</body>
</html>
