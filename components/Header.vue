<template>
  <header class="header">
    <h1>Sample</h1>
    <div class="profile">
      <p>John Doe</p>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #f2f2f2;
  padding: 16px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1 {
  margin: 0;
  font-size: 24px;
}

.profile img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
}
</style>
