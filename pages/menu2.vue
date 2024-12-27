<template>
    <div class="container">
      <main class="main-content">
        <h2>Menu 2</h2>
        <p>This is where the main content will go.</p>
      </main>
    </div>
  </template>
  
  <script>
  export default {
    name: "IndexPage",
  };
  </script>
  
  <style scoped>
  .container {
    display: flex;
    flex-direction: column;
    height: 100vh;
  }
  
  .main-content {
    flex: 1;
    padding: 16px;
    background-color: #ffffff;
    overflow-y: auto;
  }
  </style>
  