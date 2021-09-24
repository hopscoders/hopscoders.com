<template>
  <Layout>
    <section class="hero">
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-lg-4 d-flex flex-column justify-content-center mb-5 mb-md-0">
            <h1 class="text-center text-md-start text-primary mb-4 mt-4">Hi there! 🍻</h1>
            <p class="text-center text-md-start text-primary">
              We are creating something special for you. <br />Hopscoders is the
              first open source project made for the love of beer and code.
            </p>
            <p class="text-center text-md-start text-primary">
              We are passioned about homebrewing and we are trying to create
              community around it.
            </p>
            <p class="text-center text-md-start text-primary">
              If you are inrested about our plans and actions, leave us your
              email.
            </p>

            <!-- Form -->
            <div id="mc_embed_signup">
              <form
                action="https://gmail.us5.list-manage.com/subscribe/post?u=8d029421d02faf36599f3bce7&amp;id=853d50732a"
                method="post"
                id="mc-embedded-subscribe-form"
                name="mc-embedded-subscribe-form"
                class="validate mt-4"
                target="_blank"
                novalidate
              >
              
                  <div id="mc_embed_signup_scroll" class="d-flex input-group mb-3 flex-lg-nowrap">
                    <input
                      type="email"
                      value=""
                      name="EMAIL"
                      class="email w-100 form-control"
                      id="mce-EMAIL"
                      placeholder="email address"
                      required
                    />
                    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                    <div
                      style="position: absolute; left: -5000px;"
                      aria-hidden="true"
                    >
                      <input
                        type="text"
                        name="b_8d029421d02faf36599f3bce7_853d50732a"
                        tabindex="-1"
                        value=""
                      />
                    </div>
                    <!-- end of -->
                    <div class="clear input-group-append w-100 mt-3 mt-md-0">
                      <input
                        type="submit"
                        value="Subscribe"
                        name="subscribe"
                        id="mc-embedded-subscribe"
                        class="button btn btn-primary text-white w-100"
                      />
                    </div>
                  </div>

              </form>
            </div>
            <!-- End of form -->
          </div>
          <div class="col-lg-7">
            <g-image
              src="~/assets/images/illustration.svg"
              class="w-100 img-fluid"
            />
          </div>
        </div>
      </div>
    </section>
    <section class="hacktober">
      <div class="container d-flex flex-column align-items-center my-5 py-5">
        <h2 class="text-primary mt-5 mb-3">We are taking part in</h2>
        <a href="https://hacktoberfest.digitalocean.com/" target="_blank">
          <g-image
            src="~/assets/images/hacktober.svg"
            class="img-fluid my-5"
            width="400"
          />
        </a>
        <h2 class="text-primary mt-4 mb-3">Join us on:</h2>
        <a href="https://github.com/hopscoders" target="_blank">
          <g-image
            src="~/assets/images/icons/github.svg"
            class="img-fluid"
            width="50"
          />
        </a>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home",
  },
};
</script>

<style>
#mc_embed_signup_scroll {
  display: flex;
}

input {
  outline: none;
}
</style>
