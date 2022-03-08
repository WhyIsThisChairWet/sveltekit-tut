<script>
  import Title from "$lib/title.svelte";
  import "../../styles/global.css";
</script>

<header>
  <nav>
    <Title title="Ninja Gaming Guides" />
    <div class="links">
      <a href="/">Home</a>
      <a href="/about">About</a>
      <a href="/guides">Guides</a>
    </div>
  </nav>
</header>
<main>
  <slot />
</main>
<footer>
  <p>Copyright 2022 Ninja Gaming Guides</p>
</footer>

<style>
  header {
    text-align: center;
    background: rgba(0, 0, 0, 0.1);
  }
  main {
    max-width: 60rem;
    margin: 1.25rem auto;
    padding: 0 1rem;
  }
  footer {
    text-align: center;
  }
  .links {
    margin-left: auto;
  }
  a {
    margin-left: 0.625rem;
  }
  nav {
    display: flex;
    align-items: center;
    max-width: 60rem;
    margin: 0 auto;
    padding: 0 1rem;
  }
</style>
