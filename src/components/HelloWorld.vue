<template>
  <div id="content" class="site-content">
    <div class="grid-container">
      <article class="grid-item" v-for="item in test" v-bind:key="item">
        {{item.message}}
      </article>

    </div>
  </div>
</template>

<script>


export default {
  data: function() {
    return {
      test: [1,2,3,4]
    }
  }
}
</script>

<style scoped>
.grid-container {
  place-items: center;
  padding: 0.5%;
  display: grid;
  grid-template-columns: 25% 25% 25% 25%;
  grid-template-rows: 300px 300px;
  height: 800px;
  text-align: center;
  background-color: black;
}
.grid-item{
  height: 300px;
  width:100%;
  background-color: black;
  border: 2px solid #fff;
}
</style>