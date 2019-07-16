<script>
  let count = 0;

  function increment() {
    count++;
  }
</script>

<button
  on:click={increment}
  class="p-2 bg-gray-300 border-2 border-gray-500 rounded">
  {count}
</button>
