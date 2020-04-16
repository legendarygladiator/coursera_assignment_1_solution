<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MANAK - Module 2</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <style>
    * {
  box-sizing: border-box;
}
body{
  background-color: #FFA5AB;
  font-family: arial, helvetica, sans-serif;
  display: block;
  margin: 8px;
}
div{
  display: block;
}
h1, h2, h3, h4, h5, h5{
  margin: 0px;
  padding: 0px;
}
h2{
  font-size: 125%;
}
p{
  padding: 5px;
  width: 90%;
  margin-left: auto;
  margin-right: auto;
}
.container{
  padding: 10px;
}
.heading{
  margin: 50px 0px;
}
.text{
  padding-top: 50px;
}
.clear-fix{
  clear: both;
}
.bg-yellow{
  background-color: #FFCC00;
}
.bg-blue{
  background-color: #29C4FC;
}
.bg-red{
  background-color: #F53461;
}
.pull-right{
  float: right;
}
.bg-light-yellow{
  background-color: #FFD796;
}
.bg-light-blue{
  background-color: #1098F7;
}
.bg-light-red{
  background-color: #D33F49;
}
.dark-yellow{
  color: #A16300;
}
.dark-blue{
  color: #4A5899;
}
.dark-red{
  color: #C2095A;
}
.section-title{
  padding: 10px 25px;
  border: 1px solid black;
  position: absolute;
  top: -1px;
  right: -1px;
}
.section-text{
  padding-top: 50px;
}
.section{
  position: relative;
  width: 96%;
  margin: auto;
  padding: 25px;
  border: 1px solid black;
}

@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    padding:15px;
  }
  .col-lg-1 {
    width: 8.33%;
    padding:15px;
  }
  .col-lg-2 {
    width: 16.66%;
    padding:15px;
  }
  .col-lg-3 {
    width: 25%;
    padding:15px;
  }
  .col-lg-4 {
    width: 33.33%;
    padding:15px;
  }
  .col-lg-5 {
    width: 41.66%;
    padding:15px;
  }
  .col-lg-6 {
    width: 50%;
    padding:15px;
  }
  .col-lg-7 {
    width: 58.33%;
    padding:15px;
  }
  .col-lg-8 {
    width: 66.66%;
    padding:15px;
  }
  .col-lg-9 {
    width: 74.99%;
    padding:15px;
  }
  .col-lg-10 {
    width: 83.33%;
    padding:15px;
  }
  .col-lg-11 {
    width: 91.66%;
    padding:15px;
  }
  .col-lg-12 {
    width: 100%;
    padding:15px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    padding:15px;
  }
  .col-md-1 {
    width: 8.33%;
    padding:15px;
  }
  .col-md-2 {
    width: 16.66%;
    padding:15px;
  }
  .col-md-3 {
    width: 25%;
    padding:15px;
  }
  .col-md-4 {
    width: 33.33%;
    padding:15px;
  }
  .col-md-5 {
    width: 41.66%;
    padding:15px;
  }
  .col-md-6 {
    width: 50%;
    padding:15px;
  }
  .col-md-7 {
    width: 58.33%;
    padding:15px;
  }
  .col-md-8 {
    width: 66.66%;
    padding:15px;
  }
  .col-md-9 {
    width: 74.99%;
    padding:15px;
  }
  .col-md-10 {
    width: 83.33%;
    padding:15px;
  }
  .col-md-11 {
    width: 91.66%;
    padding:15px;
  }
  .col-md-12 {
    width: 100%;
    padding:15px;
  }
}

@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
    padding:15px;
  }
  .col-sm-1 {
    width: 8.33%;
    padding:15px;
  }
  .col-sm-2 {
    width: 16.66%;
    padding:15px;
  }
  .col-sm-3 {
    width: 25%;
    padding:15px;
  }
  .col-sm-4 {
    width: 33.33%;
    padding:15px;
  }
  .col-sm-5 {
    width: 41.66%;
    padding:15px;
  }
  .col-sm-6 {
    width: 50%;
    padding:15px;
  }
  .col-sm-7 {
    width: 58.33%;
    padding:15px;
  }
  .col-sm-8 {
    width: 66.66%;
    padding:15px;
  }
  .col-sm-9 {
    width: 74.99%;
    padding:15px;
  }
  .col-sm-10 {
    width: 83.33%;
    padding:15px;
  }
  .col-sm-11 {
    width: 91.66%;
    padding:15px;
  }
  .col-sm-12 {
    width: 100%;
    padding:15px;
  }
}
</style>
</head>
<body>
  <div class="container">
    <div class="heading">
      <center><h1> Our Menu </h1></center>
    </div>
    <div class="row">
      <div class="col-lg-4 col-md-6 col-sm-12">
        <div class="bg-yellow section">
          <div class="pull-right">
            <div class="section-title bg-light-yellow dark-yellow">
              <h2>Chicken</h2>
            </div>
          </div>
          <div class="clear-fix"></div>
          <div class="text">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 col-sm-12">
        <div class="bg-blue section">
          <div class="pull-right">
            <div class="section-title bg-light-blue dark-blue">
              <h2> Beef</h2>
            </div>
          </div>
          <div class="clear-fix"></div>
          <div class="text">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-12 col-sm-12">
        <div class="bg-red section">
          <div class="pull-right">
            <div class="section-title bg-light-red dark-red">
              <h2>Sushi</h2>
            </div>
          </div>
          <div class="clear-fix"></div>
          <div class="text">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
      </div>
      <div class="clear-fix"></div>
    </div>
  </body>
  </html>

