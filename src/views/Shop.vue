<template>
  <div class="home">
    <ShopPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import ShopPage from '@/components/ShopPage.vue'

export default {
  name: 'Home',
  components: {
    ShopPage
  }
}
</script>
