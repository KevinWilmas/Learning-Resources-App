<template>
  <header>
    <h1>
      {{ title }}
      <img
        src="../assets/Icon_Resources.png"
        alt="Book Logo"
        class="book-logo"
      />
    </h1>
  </header>
</template>

<script>
export default {
  props: ['title'],
};
</script>

<style scoped>
header {
  width: 100%;
  height: 5rem;
  background-color: #4258c1;
  display: flex;
  justify-content: center;
  align-items: center;
}

header h1 {
  color: white;
  margin: 0;
}

.book-logo {
  width: 60px;
  position: absolute;
  transform: translate(15px, -10px);
}
</style>
