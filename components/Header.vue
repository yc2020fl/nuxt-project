<!-- everything is inside the template and div -->
<template>
<div>

  <!-- name the slot so we can use many of them, and use v-slot to use it -->
  <!-- great for thing that are repeative -->
  <p class='headerstyle'>
    <slot name="headerontop">Header of the Site</slot>
    <slot name="headersecond">Header 2 of the Site</slot>
  </p>
</div>
</template>





<script>
export default {

}
</script>


<style lang="scss">
.headerstyle {
    font-size: 2.5em;
    background-color: #2b4c39; //green
    padding: 1em;
    color: #ffffff; //white
    //#a5a6b1; gray
}
</style>
