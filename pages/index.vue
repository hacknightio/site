<template>
  <section class="container">
    <nav class="navbar navbar-default navbar-static-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">hn</a>
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
      <h1>HackNight.io</h1>
      <div class="alert alert-dismissible alert-warning">
        Thursday, November 15, 2018
      </div>
      <p>Come join us for the initial Hackathon, featuring cash prizes and exposure to Twilio, AWS, and more. </p>
      <p>A few ground rules:</p>
      <p>
        <ol>
          <li> The first rule of HackNight is you don't recruit at HackNight </li>
          <li> The second rule of HackNight is <strong>you don't recruit at HackNight</strong> </li>
          <li> Really though, feel free to network but there are no recruiters allowed. Just engineers throwing code</li>
          <li> Be respectful, follow directions, and help out where you can. All the regular "be a good human" things apply.</li>
        </ol>
      </p>
      <br/>
      <p>
        Sound fun? It should be. Bring some friends. 
      </p>
      <div class="col-md-6 col-sm-12">
        <div class="map"></div>
        Hosted by our friends <a href="https://naativ.com" target="_blank">Naativ</a> at:
        <br/>
        <a href="https://www.google.com/maps/place/7927+High+Point+Pkwy+%23350,+Sandy,+UT+84094/@40.6150289,-111.8751317,13z/data=!4m13!1m7!3m6!1s0x8752629e33a933c9:0xe40d7ad4db04aa81!2s7927+High+Point+Pkwy+%23350,+Sandy,+UT+84094!3b1!8m2!3d40.6077476!4d-111.8558338!3m4!1s0x8752629e33a933c9:0xe40d7ad4db04aa81!8m2!3d40.6077476!4d-111.8558338" target="_blank">
          7927 High Point Pkwy #350 <br/>
          Sandy, UT 84094
        </a>
      </div>
      <div class="col-md-6 col-sm-12">
        <p>
          Want to be a good citizen and join the mailing list to let us know you'll be there?
          <br/>
          <div class="form-group">
              <!-- <label class="control-label" for="disabledInput">Mailing List</label> -->
              <input class="form-control" id="disabledInput" placeholder="... JK. We don't have one yet. Next time. " disabled="" type="text">
          </div>
        </p>
      </div>
      <div style="clear: both">
        &nbsp;
      </div>
    </div>
  </section>
</template>

<style>
.map {
  background: url('~/assets/nativeMap.png');
  width: 200px;
  height: 200px;
}
</style>