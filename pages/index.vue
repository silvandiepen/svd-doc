<template lang="pug">
div
  section.basic
    row(center)
      column(medium="2:3")
        h2 css
        table
          tr
            th selector
            th
            th declaration
            th
            th
            th
            th
          tr
            th 
            th
            th property
            th
            th value
            th
            th
          tr
            td 
              h4 .div
            td 
              h4.sub {
            td 
              h4 width
            td 
              h4.sub :
            td 
              h4 10px
            td 
              h4.sub ;
            td 
              h4.sub }

</template>

<script>
export default {};
</script>

<style lang="scss">
@import "svd-style/ext.scss";
</style>
