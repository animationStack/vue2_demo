<template>
  <div class="about">
    <h1>This is an about page</h1>
    <myRender></myRender>
    <h2></h2>
  </div>
</template>

<script>
import myRender from './components/myRender.vue'

export default{
  components: {myRender},
  data(){
    return {
      name: '关于我们'
    }
  },
  methods(){

  }, 

}
</script>
