<template> 
  <div class="container" @click:="changeNameHandler">
  {{name}} {{surname}}
  </div>
</template>
<script>
export default {
  data(){
    return{
      name: "John",
      surname: "Snower"
    }
  },
  methods:{
    changeNameHandler (){
      if(this.surname === "Snow"){
        return this.name = "Alice";
      }
    }
  },
  m
}
</script>
<style>
.container{
  color: red;
  margin: auto;
  width: 80%;
  font-size: 28px;

}
</style>
