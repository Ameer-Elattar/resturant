<template>
  <main>
    <NavViewVue />
    <HomeNavViewVue />
    <contentViewVue />
    <FooterViewVue />
  </main>
</template>

<script>
import NavViewVue from '@/components/NavView.vue'
import HomeNavViewVue from '@/components/HomeNavView.vue'
import contentViewVue from '@/components/contentView.vue'
import FooterViewVue from '@/components/FooterView.vue'

export default {
  data: () => ({}),
  components: {
    HomeNavViewVue,
    NavViewVue,
    contentViewVue,
    FooterViewVue
  }
}
</script>

<style></style>
