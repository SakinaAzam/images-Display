<template>
<div class="root">
  <h1 style="text-align: center; font-size: 50px; color: hotpink; font-style: italic;">Images are display here are in Array</h1>
<properties :img="images"/>
</div>
</template>

<script>
import Properties from './components/Properties.vue';
export default {
  components: { Properties },
  name: "App",
  data() {
    return {
      images: [
        "/src/assets/png/flo.png",
        "/src/assets/png/download.png",
        "/src/assets/png/4.png",
        "/src/assets/png/flo5.png",
        "/src/assets/png/5.png"
        
      ],
    };
  },
};
</script>

<style>
body {
  overflow-x: hidden;
  box-sizing: border-box;
}
.qoute{
  color:  #b06ab3;
  margin-top: 90px;
  text-align: center;

  font-size: 40px;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 1rem;
 padding-top: 20px;
}
img {
  width: 250px;
  height: 400px;
  border-radius: 7px;
}
</style>

