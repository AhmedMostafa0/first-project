<template>
    <section>



<Caption/>

<cards/>

    </section>

</template>

<script>

import Caption from '@/components/Contactus/caption.vue'
import cards from   '@/components/Contactus/cards.vue'


export  default{
    name: "Contactus",
    components:{
      Caption,
      cards
        

    }


}
</script>
