<template>

  

  <div class="container">
    <h2 class="text">{{ title}}</h2>
   
   </div>

   <div class="d.flex">
     <input type="text" placeholder="Enter Task" id="control" >
     
       <Button color="blue"/>
     
     
  </div>

</template>

<script>
import Button from './Butn.vue'
export default {
  name: 'Header',
  props: {
    title: String,
    
  },

  components:{
    Button,
  }
}
</script>


<style >
.d.flex{
display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
*{
    box-sizing: border-box;
}
body{
  width: 100%;
  height: 100vh;
  margin: 0em;
  padding: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(142, 231, 231);
}




input{
    outline: none;

}

ul{
    list-style: none;
    padding: 0;

}
.container{
    max-width: 800px;
    width: 100%;
    max-height: 100%;
    background-color: rgb(19, 175, 202);
    padding: 45px;
    border-radius: 25px;
    overflow: brown;
    

}
.app.header{
    font-size: 20px;
    line-height: 32px;
    margin: 0 0 12px 0;
    color: black;
}


</style>
