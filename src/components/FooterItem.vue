<script>
export default {
  name: "FooterItem",
};
</script>

<template>
  <footer class="text-white p-1">
    <div class="d-flex justify-content-around">
      <p>&longleftarrow; By Nova Siska Nurfadilah</p>
      <p></p>
      <p>&copy; Al-Qur'anku </p>
    </div>
  </footer>
</template>

<style scoped>
footer {
  font-family: Joyce;
  background-color: #a18484;
  position: fixed;
  bottom: 0;
  width: 100%;
  animation: hue-rotate 2s linear infinite alternate;
}
@keyframes hue-rotate {
  to {
    filter: hue-rotate(90deg);
  }
}
</style>
