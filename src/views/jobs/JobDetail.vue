<template>
          <!-- {{$route.params.id}} -->
  <h1>Jobs Details {{id}}</h1>
</template>

<script>
export default {
  // data(){
  //   return{
  //     id:this.$route.params.id
  //   }
  // }
  props:['id']
}
</script>

<style>

</style>