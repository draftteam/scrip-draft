<template>
  <div class="footer-wrap">
    <footer class="container">
      <hr>© 2019 Copyright - <a
        href="https://github.com/draftteam"
        target="_blank"
      >DraftTeam</a>
    </footer>
  </div>
</template>

<script>
    export default {};
</script>

<style scoped>
.footer-wrap {
  bottom: 0;
  width: 100%;
  height: 100px;
}
@media only screen and (min-width: 992px) {
  .footer-wrap {
    position: absolute;
  }
}
</style>