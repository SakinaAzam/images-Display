<template>
     <div class="container">
      <img v-bind:src="item" v-for="item in img" :key="item"  />
  </div>
</template>
<script>
export default {
    name:'properties',
    props:{
        img:Array
    }
}
</script>