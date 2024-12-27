<template>
  <aside class="sidebar">
    <ul>
      <li><a href="/menu1">Menu 1</a></li>
      <li><a href="/menu2">Menu 2</a></li>
      <li><a href="/menu3">Menu 3</a></li>
    </ul>
  </aside>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style scoped>
.sidebar {
  width: 200px;
  background-color: #e0e0e0;
  height: 100vh;
  padding: 16px;
}

.sidebar ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.sidebar li {
  margin-bottom: 16px;
}

.sidebar a {
  text-decoration: none;
  color: black;
  font-size: 18px;
}
</style>
