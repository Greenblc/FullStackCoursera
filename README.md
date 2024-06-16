# FullStackCoursera

<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Responsive Layout</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
body {
  font-family: Arial, sans-serif;
}
h1 {
  margin-bottom: 15px;
  font-size: 175%;
  text-align: center;
}

p {
  border: 1px solid black;
  background-color: #A52A2A;
  width: 90%;
  height: 150px;
  margin: 20px auto;
  padding-top: 30px;
  font-family: Helvetica;
  color: white;
  position: relative;
}

.section-title {
  position: absolute;
  top: 0;
  right: 0;
  background-color: #FFD700;
  padding: 5px;
  color: black;
  border: 1px solid black;
  font-size: 125%;
}

.row {
  width: 100%;
  margin: 0 auto;
}

/********** Large devices only **********/
@media (min-width: 992px) {
  .col-lg-4 {
    width: 33.33%;
    float: left;
  }
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6 {
    width: 50%;
    float: left;
  }
  .col-md-12 {
    width: 100%;
    float: left;
  }
}

/********** Small devices only **********/
@media (max-width: 767px) {
  .col-sm-12 {
    width: 100%;
    float: left;
  }
}
</style>
</head>
<body>
<h1>Responsive Layout</h1>

<div class="row">
  <div class="col-lg-4 col-md-6 col-sm-12">
    <p>
      <span class="section-title">Chicken</span>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </p>
  </div>
  <div class="col-lg-4 col-md-6 col-sm-12">
    <p>
      <span class="section-title">Beef</span>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </p>
  </div>
  <div class="col-lg-4 col-md-12 col-sm-12">
    <p>
      <span class="section-title">Sushi</span>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </p>
  </div>
</div>

</body>
</html>
