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
          </button>-->
          <a class="navbar-brand" href="/">
            <img src="~assets/logo.png" class="logo" />
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
            </li>-->
          </ul>
        </div>
      </div>
    </nav>
    <Hacknight5 />
    <Collapser expand-text="View past HackNights" collapse-text="Collapse past HackNights">
      <Summer2019 />
      <Hacknight4 />
      <Hacknight3 />
      <Hacknight2 />
      <Hacknight1 />
    </Collapser>
    <div class="jumbotron">
      <p>
        Want to be a good citizen and join the mailing list to let us know you'll be there?
        <br />
      </p>
      <div class="form-horizontal">
        <form
          id="mc-embedded-subscribe-form"
          action="https://hacknight.us20.list-manage.com/subscribe/post?u=55ac300faa7d7d40ceee43b86&amp;id=776caa7fad"
          method="post"
          name="mc-embedded-subscribe-form"
          class="form-inline"
          target="_blank"
          novalidate
        >
          <div class="form-group col-xs-12">
            <div class="col-sm-8">
              <input
                id="mce-EMAIL"
                type="email"
                class="form-control required email"
                value
                style="width: 100%"
                name="EMAIL"
                placeholder="purl@brocapital.com"
              />
            </div>
            <div class="col-sm-4">
              <input
                id="mc-embedded-subscribe"
                type="submit"
                value="Subscribe"
                name="subscribe"
                class="button form-control"
                style="width: 100%"
              />
            </div>
          </div>

          <div style="position: absolute; left: -5000px;" aria-hidden="true">
            <input type="text" name="b_55ac300faa7d7d40ceee43b86_776caa7fad" tabindex="-1" value />
          </div>
          <div class="clear" />
        </form>
      </div>
    </div>

    <div class="footer">
      Thanks to
      <a href="https://brobin.me/" target="_blank">Tobin Brown</a> for
      <a href="http://brobin.github.io/hacker-bootstrap/" target="_blank">this theme</a>.
    </div>
  </section>
</template>

<script>
import Hacknight1 from './hn1'
import Hacknight2 from './hn2'
import Hacknight3 from './hn3'
import Hacknight4 from './hn4'
import Hacknight5 from './hn5'
import Summer2019 from './summer2019'
import Collapser from './collapser'
export default {
  components: {
    Hacknight1,
    Hacknight2,
    Hacknight3,
    Hacknight4,
    Hacknight5,
    Summer2019,
    Collapser
  }
}
</script>

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
  padding: 10px 20px !important;
}
hr {
  border-top: 1px solid #333 !important;
}
.clear {
  clear: both;
}
.expander {
  background: #000;
  padding: 15px;
  margin-bottom: 15px;
}
.expander-link {
  display: block;
  cursor: pointer;
  text-align: right;
}
.footer {
  text-align: center;
  clear: both;
  padding: 15px 0 15px 0;
}
</style>
