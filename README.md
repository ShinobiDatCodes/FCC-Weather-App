# FCC-Weather-App
A FreeCodeCamp project for a simple local weather application.

<head>
  <title>FCC Local Weather Application</title>
  <!--Verify if this meta is really necessary, since media queries will be used on the CSS portion -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href='https://fonts.googleapis.com/css?family=Sofia' rel='stylesheet'>
</head>

<!--Verify if this code really needs "img-responsive" bootstrap, again not sure if media queries can provide responsive design features and do the same job -->
<body class="img-responsive">
  <div id="button">
    <button id="getWeather">Get Weather Information</button>
  </div>
  <!-- Verify if "container-fluid" attribute is really necessary here-->
    <div class="container-fluid">
      <!-- See if there is another way to create an efficient block without using the "jumbotron" attribute-->
    <div id="appBlock" class="jumbo">
      <div id="appContent" class="row">
        <!--Need to look at media queries to add the div below properly-->
        <div id="rightContent" class="col-12 col-m-12 col-r-12">
          <p id="ActTemp"><span id="temp"></span><span id=deg></span><span id="tempUnit" class="tempUnit"></span></p>
          <label id=switchTemp class=toggleSwitch>
            <input type=checkbox check>
              <span class="sliderBall"></span>
          </label>
          <p><span id="appTemp"></span><span id=deg2></span><span class="tempUnit"></span></p>
          <p id="weather"></p>
          <p><span id="windText">Wind: </span><span id="windSpeed"></span><span id="windUnit"> mph</span></p>
        </div>
        <div id="centerContent" class="col-12 col-m-12 col-r-12">
          <h1 id="City">Houston</h1>
          <h2 id="fullLocation">Texas, USA</h2>
        </div>
        <div id="leftContent" class="col-12 col-m-12 col-r-12">
          <p id="Time"></p>
          <p id="dayDate"></p>
        </div>

      </div>
    </div>
  </div>
</body>

<!--Added some changes to this file in order to test the GitHub Desktop-->
