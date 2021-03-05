<template>
  <div class="header" >
    <slot name="logo"></slot>
    <slot name="navbar"></slot>
  </div>
</template>

<script>


export default {
    name: 'Header',
    components:{
        
    }
}
</script>

<style scoped>

.header{
    
    background-color: black;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 10%;
}

@media screen and (max-width: 768px){
   
 
}


</style>