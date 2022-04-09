<script>
  // props with default value
  export let count = 42;

  function increment() {
    count += 1;
  }
</script>

<button on:click={increment}>count: {count}</button>

<style></style>
