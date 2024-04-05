<template>
  <div class="home">
    <!-- <HelloWorld msg="Terminal playground"/> -->
    <TextBoxCompVue />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/MainComp.vue'
import TextBoxCompVue from '@/components/TextBoxComp.vue'
export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    TextBoxCompVue
  }
}
</script>
