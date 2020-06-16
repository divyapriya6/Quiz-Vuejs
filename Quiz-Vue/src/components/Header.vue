<template>
  
    
    <p class="first"> 
        <span>Quiz App </span> <br/>
        <span>Counter: {{ numCorrect }}/{{ numTotal }}</span> 
        
    </p> 
  
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>
<style>
.first
{
    color:red;
    background-color:pink;
    
    border : 1px solid blue;
}
</style>