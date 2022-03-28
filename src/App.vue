<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Top</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#minat">Minat</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#datadiri">Data Diri</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#riwayat">Riwayat</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-heading text-uppercase">Saya Lutfi Aldri Permana</div>
          <img class="rounded-circle gambar"src="../src/assets/img/pp.jpeg" alt="" />
          <br>
          <a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#minat">Tell Me More</a>
        </div>
      </div>
    </header>

    <!-- Minat -->
    <section id="minat">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Minat</h2>
            <h3 class="section-subheading text-muted">Saya tertarik dengan</h3>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Java</h4>
            <p class="text-muted">Bahasa Pemrograman Java merupakan hal pertama yang saya pelajari dalam dunia programming, dan sampai sekarang saya akan terus mempelajarinya</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Android</h4>
            <p class="text-muted">Sekarang saya lagi gemar-gemarnya mempelajari android, dan suka mengoprek os android.</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">PowerPoint</h4>
            <p class="text-muted">Saat ini saya juga senang mengotak atik power point untuk design postingan sosial media, slide presentasi, dll.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Minat -->
    <section id="datadiri">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Data Diri</h2>
            <h3 class="section-subheading text-muted">Siapa saya?</h3>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Tempat Lahir</h4>
            <p class="text-muted">Rimba Jaya</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Tanggal Lahir</h4>
            <p class="text-muted">17 April 2002</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Umur</h4>
            <p class="text-muted">19 Tahun</p>
          </div>
        </div>
      </div>
    </section>

    <!-- riwayat -->
    <section id="riwayat">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Riwayat</h2>
            <h3 class="section-subheading text-muted">Perjalanan Hidup Saya</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="../src/assets/img/baby.png" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2002</h4>
                    <h4 class="subheading">Saya terlahir menjadi manusia!</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Saya Lahir di Rimba Jaya</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="../src/assets/img/sd.png" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2008</h4>
                    <h4 class="subheading">Saya menginjak Pendidikan Sekolah Dasar</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Saya tamatan SDN 013 Ujungbatu</p>
                  </div>
                </div>
              </li>
              <li>
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="../src/assets/img/smp.png" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2014</h4>
                    <h4 class="subheading">Saya menginjak Pendidikan Sekolah Menengah Pertama</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Saya tamatan SMPN 017 Pekanbaru</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="../src/assets/img/sma.png" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2017</h4>
                    <h4 class="subheading">Saya menginjak Pendidikan Sekolah Menengah Atas</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Saya tamatan SMAN 15 Pekanbaru</p>
                  </div>
                </div>
              </li>
              <li>
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="../src/assets/img/graduated.png" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>Now</h4>
                    <h4 class="subheading">Saya menginjak Perguruan Tinggi</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Saya tergabung dalam Keluarga Teknik Informatika di Universitas Islam Negeri Sultan Syarif Kasim Riau</p>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>


    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading">Contact Us</h2>
            <h3 class="section-subheading text-muted">Hubungi Saya!.</h3>
            <img id="gambarContact" class="rounded-circle img-fluid" src="../src/assets/img/pp.jpeg" alt="">
          </div>
        </div>
        <br>
        <div class="row">
          <div class="col-lg-12">
            <form id="contactForm" name="sentMessage" novalidate="novalidate">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <input class="form-control" id="name" type="text" placeholder="Your Name *" required="required" data-validation-required-message="Please enter your name.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="email" type="email" placeholder="Your Email *" required="required" data-validation-required-message="Please enter your email address.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="phone" type="tel" placeholder="Your Phone *" required="required" data-validation-required-message="Please enter your phone number.">
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <textarea class="form-control" id="message" placeholder="Your Message *" required="required" data-validation-required-message="Please enter a message."></textarea>
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="clearfix"></div>
                <div class="col-lg-12 text-center">
                  <div id="success"></div>
                  <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase" type="submit">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy;2022</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-twitter"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-facebook-f"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a href="#">Privacy Policy</a>
              </li>
              <li class="list-inline-item">
                <a href="#">Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
