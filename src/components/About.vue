<template>
  <div class="about">
    <h1>Hello friend, this is an about page</h1>
    <p>This single page app was made in order to learn Vue.js with routing.</p>
    <p>It was made using this <a :href="resource" target="_blank">tutorial</a></p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data(){
    return{
      resource:"https://github.com/designcourse/vue2-tutorial"
    }
  },
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  scoped>
  
</style>
