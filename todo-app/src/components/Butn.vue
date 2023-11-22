<template>
    <button :style="{background: color }" class="btn"> Add
     </button>
     <button  :style="{background: color }" class="btn"> Remove
     </button>
</template>
<script>
export default {
    name:'Button',
    props:{
        Text: String,
        color: String,
    
    },
    
}


</script>

<style scoped>
.btn{
    
    color: lightgoldenrodyellow;
    border: none;
    border-radius: 5px;
    padding: 10px 40px;
    font-size: 16px;
    display: inline-block;
    cursor: pointer;
    text-decoration: none;
    font-family: inherit;
}
</style>
