<template>
  <Layout>
    <!-- NAVBAR -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white">
      <div class="container">

        <!-- Brand -->
        <a class="navbar-brand" href="./index.html">
          <g-image alt="" width="50px" src="~/logo.png" class="navbar-brand-img"/>
        </a>

        <!-- Toggler -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <!-- Collapse -->
        <div class="collapse navbar-collapse" id="navbarCollapse">

          <!-- Toggler -->
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <i class="fe fe-x"></i>
          </button>

          <!-- Button -->
<!--          <a class="navbar-btn btn btn-sm btn-primary lift ms-auto" href="https://themes.getbootstrap.com/product/landkit/" target="_blank">-->
<!--            Subscribe-->
<!--          </a>-->

        </div>

      </div>
    </nav>

    <!-- WELCOME -->
    <section class="pt-4 pt-md-11">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-12 col-md-5 col-lg-6 order-md-2">

            <!-- Image -->
            <g-image alt="" src="~/illustration.png" class="img-fluid mw-md-150 mw-lg-130 mb-6 mb-md-0" />
<!--            <img src="assets/img/illustrations/illustration-2.png" class="img-fluid mw-md-150 mw-lg-130 mb-6 mb-md-0" alt="..." data-aos="fade-up" data-aos-delay="100">-->

          </div>
          <div class="col-12 col-md-7 col-lg-6 order-md-1" data-aos="fade-up">

            <!-- Heading -->
            <h1 class="display-3 text-center text-md-start" style="color: #662924">
              Hi there! 🍻
            </h1>

            <!-- Text -->
            <p class="lead text-center text-md-start mb-6 mb-lg-8" style="color: #662924">
              We are creating something special for you.
              Hopscoders is the first open source project made
              for the love of beer and code.
            </p>
            <p class="lead text-center text-md-start mb-6 mb-lg-8" style="color: #662924">

              We are passioned about homebrewing and
              we are trying to create community around it.
            </p>
            <p class="lead text-center text-md-start mb-6 mb-lg-8" style="color: #662924">
              If you are inrested about our plans and actions,
              leave us your email.
            </p>

            <!-- Buttons -->
<!--            <div class="text-center text-md-start">-->

<!--              <a href="#" class="btn btn-primary">-->
<!--                Subscribe-->
<!--              </a>-->
<!--            </div>-->

          </div>
        </div> <!-- / .row -->
      </div> <!-- / .container -->
    </section>


    <!-- FOOTER -->
<!--    <footer class="py-8 py-md-11 bg-gray-200">-->
<!--      <div class="container">-->
<!--        <div class="row">-->
<!--          <div class="col-12 col-md-4 col-lg-3">-->

<!--            &lt;!&ndash; Brand &ndash;&gt;-->
<!--            <g-image alt="Example image" src="~/logo.png" class="footer-brand img-fluid mb-2"/>-->

<!--            &lt;!&ndash; Text &ndash;&gt;-->
<!--            <p class="text-gray-700 mb-2">-->
<!--              A better way to build.-->
<!--            </p>-->

<!--            &lt;!&ndash; Social &ndash;&gt;-->
<!--            <ul class="list-unstyled list-inline list-social mb-6 mb-md-0">-->
<!--              <li class="list-inline-item list-social-item me-3">-->
<!--                <a href="#!" class="text-decoration-none">-->
<!--                  <img src="" class="list-social-icon" alt="...">-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="list-inline-item list-social-item me-3">-->
<!--                <a href="#!" class="text-decoration-none">-->
<!--                  <img src="" class="list-social-icon" alt="...">-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="list-inline-item list-social-item me-3">-->
<!--                <a href="#!" class="text-decoration-none">-->
<!--                  <img src="" class="list-social-icon" alt="...">-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="list-inline-item list-social-item">-->
<!--                <a href="#!" class="text-decoration-none">-->
<!--                  <img src="" class="list-social-icon" alt="...">-->
<!--                </a>-->
<!--              </li>-->
<!--            </ul>-->

<!--          </div>-->
<!--          <div class="col-6 col-md-4 col-lg-2">-->

<!--            &lt;!&ndash; Heading &ndash;&gt;-->
<!--            <h6 class="fw-bold text-uppercase text-gray-700">-->
<!--              Products-->
<!--            </h6>-->

<!--            &lt;!&ndash; List &ndash;&gt;-->
<!--            <ul class="list-unstyled text-muted mb-6 mb-md-8 mb-lg-0">-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Page Builder-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  UI Kit-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Styleguide-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Documentation-->
<!--                </a>-->
<!--              </li>-->
<!--              <li>-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Changelog-->
<!--                </a>-->
<!--              </li>-->
<!--            </ul>-->

<!--          </div>-->
<!--          <div class="col-6 col-md-4 col-lg-2">-->

<!--            &lt;!&ndash; Heading &ndash;&gt;-->
<!--            <h6 class="fw-bold text-uppercase text-gray-700">-->
<!--              Services-->
<!--            </h6>-->

<!--            &lt;!&ndash; List &ndash;&gt;-->
<!--            <ul class="list-unstyled text-muted mb-6 mb-md-8 mb-lg-0">-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Documentation-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Changelog-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Pagebuilder-->
<!--                </a>-->
<!--              </li>-->
<!--              <li>-->
<!--                <a href="#!" class="text-reset">-->
<!--                  UI Kit-->
<!--                </a>-->
<!--              </li>-->
<!--            </ul>-->

<!--          </div>-->
<!--          <div class="col-6 col-md-4 offset-md-4 col-lg-2 offset-lg-0">-->

<!--            &lt;!&ndash; Heading &ndash;&gt;-->
<!--            <h6 class="fw-bold text-uppercase text-gray-700">-->
<!--              Connect-->
<!--            </h6>-->

<!--            &lt;!&ndash; List &ndash;&gt;-->
<!--            <ul class="list-unstyled text-muted mb-0">-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Page Builder-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  UI Kit-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Styleguide-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Documentation-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Changelog-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Documentation-->
<!--                </a>-->
<!--              </li>-->
<!--              <li>-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Changelog-->
<!--                </a>-->
<!--              </li>-->
<!--            </ul>-->

<!--          </div>-->
<!--          <div class="col-6 col-md-4 col-lg-2">-->

<!--            &lt;!&ndash; Heading &ndash;&gt;-->
<!--            <h6 class="fw-bold text-uppercase text-gray-700">-->
<!--              Legal-->
<!--            </h6>-->

<!--            &lt;!&ndash; List &ndash;&gt;-->
<!--            <ul class="list-unstyled text-muted mb-0">-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Documentation-->
<!--                </a>-->
<!--              </li>-->
<!--              <li class="mb-3">-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Changelog-->
<!--                </a>-->
<!--              </li>-->
<!--              <li>-->
<!--                <a href="#!" class="text-reset">-->
<!--                  Pagebuilder-->
<!--                </a>-->
<!--              </li>-->
<!--            </ul>-->

<!--          </div>-->
<!--        </div> &lt;!&ndash; / .row &ndash;&gt;-->
<!--      </div> &lt;!&ndash; / .container &ndash;&gt;-->
<!--    </footer>-->

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
