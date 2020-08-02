<script>
  import Header from "./components/header.svelte";
  import Baner from "./components/Baner.svelte";
  let name = "mamang";
</script>

<style>
  main {
    margin-top: 70px;
    padding: 20px 20px;
  }
</style>

<Header title="learn svelte" />
<main>
  <Baner />
  <Baner />
  <Baner />
  <Baner />
  <h1 class="text-danger">Hello {name}!</h1>
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
  <button on:click={() => alert('oke')} class="btn btn-primary">haloo</button>
</main>
