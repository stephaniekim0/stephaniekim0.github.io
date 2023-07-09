<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {background-color: #006100;}


/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

.left {
  width: 30%;
  color: #FBFAF2;
}

.right {
  width: 70%;
  color: #FBFAF2;
}


/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.myclass {
  display: inline-block;
  width: 15%;
  padding: 0%;
}
</style>
</head>
<body>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Stephanie Kim</h2>
    <p>CS and Biology Student</p><br>
     <p style="margin-left: 25px;">
     ⸺ About<br>
     ⸺ Experiences<br>
     ⸺ Skills<br>
     ⸺ Projects
  </div>
  <div class="column right" style="background-color:#bbb;">
    <h2>Hi!</h2>
    <p>I'm a rising junior at Swarthmore College pursuing a double major in Computer Science and Biology. I am interested in Software Engineering, Computational Biology, Machine Learning, and more. Look around my page to learn more about my timeline!</p>
    <p class="myclass">
  Jan 2023 - Present
</p>
<p class="myclass">
  Conservation Biology Lab
</p>
  </div>
</div>

</body>
</html>
