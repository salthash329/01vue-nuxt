<template>
  <section class="container">
    <nuxt-link to="/users">Users</nuxt-link>
  </section>
  
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>

<script>
export default {
  layout: 'users'
}
</script>
