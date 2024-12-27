<template>
  <div class="container">
    <main class="main-content">
      <h2>Menu 1</h2>
      <p>This is where the main content will go.</p>
      <table class="data-table">
        <thead>
          <tr>
            <th>ID</th>
            <th>Sender</th>
            <th>App Name</th>
            <th>Jam</th>
            <th>Jam Update</th>
            <th>Aksi</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>John Doe</td>
            <td>App A</td>
            <td>10:00</td>
            <td>10:30</td>
            <td><button>Update</button></td>
          </tr>
          <tr>
            <td>2</td>
            <td>Jane Smith</td>
            <td>App B</td>
            <td>11:00</td>
            <td>11:15</td>
            <td><button>Update</button></td>
          </tr>
        </tbody>
      </table>
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

.data-table {
  margin-top: 20px;
  width: 100%;
  border-collapse: collapse;
}

.data-table th,
.data-table td {
  padding: 8px 12px;
  text-align: left;
  border: 1px solid #ddd;
}

.data-table th {
  background-color: #f4f4f4;
}

.data-table button {
  padding: 6px 12px;
  background-color: #4CAF50;
  color: white;
  border: none;
  cursor: pointer;
}

.data-table button:hover {
  background-color: #45a049;
}
</style>
