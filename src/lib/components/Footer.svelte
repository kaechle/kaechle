<script>
  let currentYear = new Date().getFullYear()
</script>

<footer>
  <p>Copyright © Me {currentYear}.</p>
</footer>

<style lang="postcss">
  footer {
    display: flex;
    width: 100%;
    justify-content: center;

    p {
      font-size: 0.85em;
      color: hsla(0, 0%, 50%, 1);
      margin: 4em auto;
    }
  }
</style>
