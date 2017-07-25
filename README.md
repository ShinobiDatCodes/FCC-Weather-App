# FCC-Weather-App
A FreeCodeCamp project for a simple local weather application.

<head>
  <title>Local Weather</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href='https://fonts.googleapis.com/css?family=Sofia' rel='stylesheet'>
</head>

<body class="img-responsive">
  <div id="button">
    <button id="getWeather">Get Weather Information</button>
  </div>
  <!--<p id=message2></p>-->
  <div class="container-fluid">
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
