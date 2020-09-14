<template>
  <div class="home">
    <HomeText msg="Zach's Borgers"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeText from '@/components/HomeText.vue'

export default {
  name: 'Home',
  components: {
    HomeText
  }
}
</script>
