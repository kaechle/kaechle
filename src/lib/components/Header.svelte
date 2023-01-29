<script>
</script>

<header>
  <img src="./images/logo.svg" alt="a logo" />
  <menu>
    <li><a href="/about" class="href">About</a></li>
    <li><a href="/blog" class="href">Blog</a></li>
    <li><a href="/contact" class="href">Contact</a></li>
  </menu>
</header>

<style lang="postcss">
  header {
    display: flex;
    justify-content: space-between;
    margin: 1em 6em;
  }

  img {
    width: 3em;
  }

  menu {
    display: flex;
    list-style: none;
    font-family: var(--font-headers);
    text-transform: uppercase;
    font-size: 0.895rem;

    li {
      margin: 0 2em;
    }
  }
</style>
