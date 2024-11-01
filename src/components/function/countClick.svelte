<script>
  let count = $state(0);

  function increment() {
    count++;
  }

  function resetCount() {
    count = 0;
  }
</script>

<!-- count -->
<div class="count">
  <span>
    <button class="b1" on:click={increment}> Click me </button>
    <button class="b2" on:click={resetCount}> Reset </button>
  </span>

  <h1>
    {count}
    <!-- Ternary condition -->
    {count <= 1 ? "Time" : "Times"}
  </h1>
</div>

<style>
  .count {
    width: auto;
    text-align: center;
    background-color: antiquewhite;
    padding: 40px;
    button {
      padding: 10px 20px;
      font-size: 18px;
      border-radius: 6px;
      color: white;
      border: none;
    }

    button.b1 {
      background-color: rgb(59, 187, 59);
    }
    button.b2 {
      background-color: rgb(243, 70, 70);
    }

    h1 {
      color: blue;
    }
  }
</style>
