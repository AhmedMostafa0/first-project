<template>
    <section class="Slider position-relative">
     <div class="caption position-absolute top-50 start-50 translate-middle" >
     <h6>Design/ Development/ photography</h6>
     <h1>CREATIVITY HAVE NEW LEVEL</h1>
     <a class="btn career me-4"> preview</a>  
     <a class="btn career">Get theme</a>
     </div>

    </section>




</template>

<style>
 .Slider{

     background: url("../assets/imgs/header.jpg");
     background-size: cover;
     background-color: var(--second-color);
     background-blend-mode: multiply;
     height: 85vh;
     color: var(--white);

 }


.Slider .caption .career{
   color: var(--white);
   font-size: bold;
   font-size: calc(var(--default-font-size)+ 2px);
   border: 1px solid var(--white);

}

.Slider .caption .career:hover{
    background-color: var(--main-color);
    border: 1px solid var(--main-color);
}



</style>

<script>
export default {
    name: "Slider"
}
</script>