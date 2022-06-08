<script>
</script>

<main>
  <span class="body">
    <img class="niels" alt="niels" src="/niels_bw.jpg" />
    <img class="map" alt="map" src="/map.svg" />
    <br />
    <br />
    <div class="grey">
      <h1>Dan Humphries</h1>
      <p>Freelance web engineer • multidisplinary Artist</p>
      <p>&nbsp;&nbsp;&nbsp;&nbsp;ldn • pdx</p>
      <p>&nbsp;&nbsp;&nbsp;&nbsp;-</p>
    </div>
    <div class="grey body__left">
      <h3>web</h3>
      <p>hedron hackerspace • web • 2022</p>
    </div>
    <div class="grey body__right">
      <h3>art</h3>
      <p>metamodernism as a service • instagram • 2021</p>
      <p>vivi (mas + theremin) • bauhaus fm • 2021</p>
      <p>computational soul • bartlett school of architecture • 2022</p>
    </div>
    <div class="grey body__left">
      <h3>wip</h3>
      <!--p>die natur • pdx</p-->
      <p>conversations • essay</p>
      <p>pandora's box • twitter</p>
      <p>signalling dissent • photo essay</p>
      <p>rubik's world • kings college london</p>
    </div>
    <div class="body__right">
      <h3>contact</h3>
      <p>
        <a href="https://www.instagram.com/dn.niels">instagram</a>
        •
        <a href="mailto: dan@aufbau.io">email</a>
        •
        <a href="https://www.linkedin.com/in/dan-humphries/">linkedin</a>
      </p>
    </div>
    <br />
    <br />
  </span>
</main>

<style>
  main {
    text-align: center;
    margin-top: 3rem;
  }

  h1 {
    font-family: "dahlia", sans-serif;
    color: #171717;
    font-size: 3em;
    font-weight: 100;
    margin: 1rem 0 2.5rem 0;
  }

  h3 {
    font-family: "dahlia", sans-serif;
    color: #171717;
  }

  .map {
    position: absolute;
    width: 100%;
    width: 100%;
    left: 0;
    top: 10rem;
    transform: translateY(-60%);
    z-index: -1;
  }

  .body {
    display: float;
  }

  .grey {
    background: #f0f0f0;
  }

  .body__left {
    text-align: left;
  }

  .body__right {
    margin: 0.1em;
    text-align: right;
  }

  @media (max-width: 800px) {
    .niels {
      width: 100%;
    }

    .map {
      width: 200%;
    }
  }
</style>
