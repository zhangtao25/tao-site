<template>
  <div>
    <my-nav />

    <nuxt />

    <my-footer />
  </div>
</template>

<script>
import MyNav from '~/components/MyNav'
import MyFooter from '~/components/MyFooter'

export default {
  middleware: 'global',
  components: {
    MyNav,
    MyFooter
  }
}
</script>
