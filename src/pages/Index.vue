<template>
  <Layout>
    <div class="container">
      <div class="d-flex justify-content-between align-items-start">
          <g-image src="~/assets/images/logo.svg" width="80"/>
          <div class="d-flex align-items-center">
            <p class="mb-0 text-primary">Follow us</p>
            <span class="mx-3 text-primary">|</span>
            <g-image src="~/assets/images/icons/github.svg" width="30"/>
          </div>
      </div>
      <div class="row">
        <div class="col-md-5 d-flex flex-column justify-content-center pe-lg-5">
          
            <h1 class="text-primary">Hi there! 🍻</h1>
            <p class="text-primary">
              We are creating something special for you. Hopscoders is the first
              open source project made for the love of beer and code.
            </p>
            <p class="text-primary">
              We are passioned about homebrewing and we are trying to create
              community around it.
            </p>
            <p class="text-primary">
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
              class="validate"
              target="_blank"
              novalidate
            >
              <div id="mc_embed_signup_scroll">
                <input
                  type="email"
                  value=""
                  name="EMAIL"
                  class="email"
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
                <div class="clear">
                  <input
                    type="submit"
                    value="Subscribe"
                    name="subscribe"
                    id="mc-embedded-subscribe"
                    class="button"
                  />
                </div>
              </div>
            </form>
          </div>
          <!-- End of form -->
        </div>
        <div class="col-md-7">
          <g-image src="~/assets/images/illustration.svg" class="img-fluid"/>
        </div>
      </div>
    </div>
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
