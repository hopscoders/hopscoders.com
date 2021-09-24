<template>
  <div>
    <h-navbar></h-navbar>
    <slot></slot>
    <h-footer></h-footer>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import HNavbar from '~/components/Navbar.vue'
import HFooter from '~/components/Footer.vue'
export default {
  components: {
    HNavbar,
    HFooter
  }
}
</script>
