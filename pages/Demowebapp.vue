<template>
  <div>
    <h1> Demo web app </h1>
    <Demoapp/>
  </div>
</template>

<script>

  import Demoapp from './Demoapp.vue';

export default  {
components : {
  Demoapp
},
  data () {
    items: [{}, {}]
  },
}


</script>
