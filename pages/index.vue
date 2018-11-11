<template>
  <section class="container">
    <nav class="navbar navbar-default navbar-static-top">
        <div class="container">
            <div class="navbar-header">
                <!-- <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button> -->
                <a class="navbar-brand" href="/">
                  <img src="~assets/logo.png" class="logo">
                  hacknight.io
                </a>
            </div>
            <div id="navbar" class="navbar-collapse collapse">
                <ul class="nav navbar-nav navbar-right">
                    <!-- <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Not a Menu... yet<span class="caret"></span> </a>
                        <ul class="dropdown-menu" role="menu">
                            <li><a>Really, it's not</a></li>
                            <li class="divider"></li>
                            <li><a>I promise</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="//reddit.com/r/itsaunixsystem" target="_blank">H4x0rs Only</a>
                    </li> -->
                </ul>
            </div>
        </div>
    </nav>
    <div class="jumbotron">
      <h1>HackNight #1</h1>
      <div class="alert alert-dismissible alert-warning">
        Thursday, November 15, 2018 @ 6:30
      </div>
      <p>
        Come join us for the initial Hackathon, featuring cash prizes and exposure to Twilio, 
        AWS, and more. 
      </p>
      <p>
        Also, we'll have a 
        <a href="https://www.youtube.com/watch?v=dX1x47UG6VI" target="_blank">Magic Leap Augmented Reality rig</a>
        setup and some 
        <a href="https://techcrunch.com/2018/10/18/twilio-launches-a-new-sim-card-and-narrowband-dev-kit-for-iot-developers/" target="_blank">nifty Raspberry-Pi-like circuits</a>          
        for playing with, gift cards as door prizes, and (hopefully Pie Pizzeria) pizza.
      </p>
      <hr/>
      <p>A few ground rules:</p>
      <p>
        <ol>
          <li> The first rule of HackNight is you don't recruit at HackNight. </li>
          <li> The second rule of HackNight is <strong class="underline">you don't recruit at HackNight</strong>. </li>
          <li> Really though, feel free to network but there are no recruiters allowed. Just engineers throwing code.</li>
          <li> Be respectful, follow directions, and help out where you can. All the regular "be a good human" things apply.</li>
        </ol>
      </p>
      <br/>
      <p>
        Sound fun? It should be. Bring some friends. Or make some there.
      </p>
      <hr/>
      <div class="col-md-6 col-sm-12 no-pad align-center">
        <img class="map" src="~assets/naativMap.png">
        <br/>
        Hosted by our friends <a href="https://naativ.com" target="_blank">Naativ</a> at:
        <br/>
        <a href="https://www.google.com/maps/place/7927+High+Point+Pkwy+%23350,+Sandy,+UT+84094/@40.6150289,-111.8751317,13z/data=!4m13!1m7!3m6!1s0x8752629e33a933c9:0xe40d7ad4db04aa81!2s7927+High+Point+Pkwy+%23350,+Sandy,+UT+84094!3b1!8m2!3d40.6077476!4d-111.8558338!3m4!1s0x8752629e33a933c9:0xe40d7ad4db04aa81!8m2!3d40.6077476!4d-111.8558338" target="_blank">
          7927 High Point Pkwy #350 <br/>
          Sandy, UT 84094
        </a>
        <br/>
        <br/><br/>
      </div>
      <div class="col-md-6 col-sm-12 no-pad">
        <p>
          Want to be a good citizen and join the mailing list to let us know you'll be there?
          <br/>
          <div class="form-group">
              <!-- <label class="control-label" for="disabledInput">Mailing List</label> -->
              <input class="form-control" id="disabledInput" placeholder="... JK. We don't have one yet... " disabled="" type="text">
          </div>
        </p>
      </div>
      <div class="footer">
        Thanks to <a href="https://brobin.me/" target="_blank">Tobin Brown</a> for 
        <a href="http://brobin.github.io/hacker-bootstrap/" target="_blank">this theme</a>.
      </div>
    </div>
  </section>
</template>

<style>
a {
  text-decoration-line: underline;
  text-decoration-style: dotted;
}
.underline {
  text-decoration: underline;
}

.logo {
  width: 25px;
  display: inline-block !important;
}
.navbar-header a {
  text-decoration: none;
}
.map {
  width: 306px;
  height: 200px;
  margin-bottom: 10px;
}
.align-center {
  text-align: center;
}
.no-pad {
  padding-left: 0;
  padding-right: 0;
}
.jumbotron {
  padding: 1px 20px !important;
}
hr {
  border-top: 1px solid #333 !important;
}
.footer {
  text-align: center;
  clear: both;
  padding: 15px 0 15px 0;
}
</style>