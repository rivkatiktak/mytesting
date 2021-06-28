<template>
  <div v-bind:class="classthis" class="cube">
   
      <input type="checkbox" value="true" name="thisButton" @change="inputchange($event)" 
      />
  </div>
</template>


<script>
export default {
  name: 'Schedule',
 
  data(){
   return {
         classthis:'color-green',
         }
 },
 computed:{

 },
  methods:{
   inputchange:function($event) {
    
     this.classthis= $event.target.checked?'color-red':'color-green';
    console.log(this.$classthis)
   },
   
  }
}
</script>
<style scoped>
.color-green{
  background-color:green;
}
.color-red{
  background-color:red;
}
.cube{
  width:120px;
  height: 120px;
}
</style>