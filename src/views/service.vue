<template>
    <section>

      <Caption/>
      <Cards/>
    </section>
    
</template>


<script>

import Caption from '../components/service/caption.vue'
import Cards from   '../components/service/cards.vue'

export default{
  
  
    name: "Service",
    components:{
         Caption,
         Cards
    } 
        
    
}
</script>
