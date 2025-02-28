<script>
  let name = "World";
</script>

<main>
  <h1>Hello {name}!</h1>
  <input bind:value={name} placeholder="TT Enter your name" />
</main>

<style>
  main {
    text-align: center;
    padding: 2rem;
    font-family: Arial, sans-serif;
  }
  input {
    margin-top: 1rem;
    padding: 0.5rem;
    font-size: 1rem;
  }
</style>
