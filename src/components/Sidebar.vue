<template>
  <div class="sidebar">
    <h1>{{ title }}</h1>
    
  </div>
</template>

<script>
export default {
  name: "Sidebar",
  data() {
    return {
      title: "Commuting cast"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sidebar {
  grid-column: 1 / 1;
  padding: 0 10%;
}

h1 {
  font-weight: normal;
  text-align: center;
}
</style>
