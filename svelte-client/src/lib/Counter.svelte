<script>
  import { calc } from "../utils/Calc";

  let count = 0
  const increment = () => {
    count = calc(count, 1);
  }
</script>

<button on:click={increment}>
  count is {count}
</button>
