<template>
  <aside class="sidebar">
    <ul>
      <li><a href="/client">Daftar Client</a></li>
      <li><a href="/message">Message</a></li>
      <li><a href="/log">Log</a></li>
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
