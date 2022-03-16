<template>
  <h1>Jobs</h1>
  <div class="color" v-for="job in jobs" :key="job.id">
      <h1>{{job.position}} | {{job.hero}}</h1>
  </div>
</template>

<script>
export default {
    data(){
        return{
            jobs:[
                {id:"1",position:"Top laner",hero:"Jayce , Kennen , Rekneton"},
                {id:"2",position:"Mid laner",hero:"Corki , Ahri , Brand"},
                {id:"3",position:"ADC",hero:"Ashe , Ezreal , Varus"}
            ]
        }
    }
}
</script>

<style>
    .color{
        color: crimson;
    }
</style>