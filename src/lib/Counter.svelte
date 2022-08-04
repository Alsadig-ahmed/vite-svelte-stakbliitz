<script>
  let count = 0
  const increment = () => {
    count += 12
  }
</script>

<button on:click={increment}>
  count is {count}
</button>
