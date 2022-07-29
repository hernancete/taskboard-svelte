<script>
  import Counter from "./lib/Counter.svelte";
</script>

<main class="container-fluid">
  <h1>Task Board</h1>

  <div class="grid">
    <div>col 1</div>
    <div>col 2</div>
    <div>col 3</div>
  </div>

  <div class="card">
    <Counter />
  </div>
</main>

<style>
  main {
    text-align: center;
  }
</style>
