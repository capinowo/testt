<template>
  <div>
    <Header />
    <div class="layout">
      <Sidebar />
      <main>
        <NuxtPage />
      </main>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Sidebar from "@/components/Sidebar.vue";

export default {
  components: { Header, Sidebar },
};
</script>

<style>
.layout {
  display: flex;
}

main {
  flex: 1;
  padding: 16px;
}
</style>
